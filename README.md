ShaderMask(shaderCallback: (Rect bounds) {
    return RadialGradient(
    center: Alignment.topLeft,
    radius: 1.0,
    colors: <Color>[Colors.white, Colors.black],
    tileMode: TileMode.mirror,
    ).createShader(bounds);
    },blendMode: BlendMode.color,
                        child: Image.file(File(widget.controller.image!.value),fit: BoxFit.cover,
                        ),
                      ),
  
  
  
  
  // This is color filter base for images 
