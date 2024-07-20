# NextBreakpoint Converted Libraries

NextBreakpoint Converted Libraries is a collection of Java modules created converting libraries which are not yet distributed as modules.

Please note the conversion is a temporary workaround until the authors of the libraries release a new version which is a Java module. 


## License

NextBreakpoint Converted Libraries is distributed under the terms of BSD 3-Clause License.

    Copyright (c) 2024, Andrea Medeghini
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are met:

    * Redistributions of source code must retain the above copyright notice, this
        list of conditions and the following disclaimer.

    * Redistributions in binary form must reproduce the above copyright notice,
        this list of conditions and the following disclaimer in the documentation
        and/or other materials provided with the distribution.

    * Neither the name of the copyright holder nor the names of its
        contributors may be used to endorse or promote products derived from
        this software without specific prior written permission.

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
    AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
    IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
    DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
    FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
    DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
    SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
    CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
    OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
    OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

NextBreakpoint Converted Libraries contain copy of binaries files from the following open source libraries:

    - ANTLR4 Runtime
    - Apache Common Math3
    - RichTextFX and dependencies ReactFX, Flowless, UndoFX, WellbehavedFX


## Get binaries

NextBreakpoint Converted Libraries is available in Maven Central Repository and [GitHub](https://github.com/nextbreakpoint/converted-libraries).

If you are using Maven, this is the list of the dependencies you can add to your POM to start using the converted libraries:

    <dependency>
        <groupId>com.nextbreakpoint</groupId>
        <artifactId>com.nextbreakpoint.convertedlibraries.antlr4-runtime</artifactId>
        <version>1.0.0</version>
    </dependency>

    <dependency>
        <groupId>com.nextbreakpoint</groupId>
        <artifactId>com.nextbreakpoint.convertedlibraries.commons-math3</artifactId>
        <version>1.0.0</version>
    </dependency>

    <dependency>
        <groupId>com.nextbreakpoint</groupId>
        <artifactId>com.nextbreakpoint.convertedlibraries.richtextfx-with-dependencies</artifactId>
        <version>1.0.0</version>
    </dependency>
