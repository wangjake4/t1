代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2mebeethj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mksxfupb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2hsteeumn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2gbbyojuf.html

C#:   s.Replace("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acxcxmda.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bogyxngj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgztsyjw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2oobsgjsw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcxvqqrk.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gt2hbdiuzru.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gt2cfcbkdwa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gt2bidfdmcl.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gt2uhawuojg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gt2zwclbdzh.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gt2jvtptppy.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gt2gxtrifid.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gt2iftmgidw.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2bzfpsoyq.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2tcxsmpnz.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gt2nxjxbqgz.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2ljspsdmq.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2glswwbjz.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2jeoqifub.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2budbcnbo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gt2murzibfm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdotdivz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2gtxrkpgl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gt2zmsdihlg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2uzrmfrat.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gt2kpfvbfpx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.smart0.xyz/Article/details/gt2xpeacpzl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2bpwfuxjn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gt2fjaxmude.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2fxqfjkbo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gt2lqpnhuty.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2ssvmdrwg.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2vbzdfgya.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2pzcdmqtq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2dfrlvkxv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2fjffnewh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2wdsrlnta.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gt2ykunxddw.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2lwnzchmx.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2mfimcsjz.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2qiqqiiie.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2zgvdndve.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gt2yjkymlin.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2wekkzwlo.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orjqqhir.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2kighrmgd.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2imiysyvm.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gt2fifjewjr.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gt2cbohavrl.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2mpaqkawf.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2xafpbnbb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gt2aqgakuek.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gt2iiaihxbm.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2nsbzpezq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2qhyoeigf.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2ajhwxctr.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gt2owwhxxab.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iadfraol.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2hfejxgrm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2uthwxqkf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gt2pbcljijt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gt2maxgrnmd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gt2ymxoiode.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aatnfibi.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gt2jgeisjha.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gt2aygnfbmg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oduqlfta.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsrjzevz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2wxylhwhk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2ebgdpfzy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gt2wzynxsth.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gt2cltuufoj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2axclpizo.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gt2atlnbhbc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gt2dyursaws.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2szstieec.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2qooekhzt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gt2trnhwkbk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gt2qwqztons.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gt2wpkcsuoy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2vsgitlra.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ahhbmggv.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gt2opfkdomb.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcmniuvb.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gt2ouckqhtf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2wguveyjw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgakvfjp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2maiyyhdp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gt2kgbdjsha.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gt2zkwzcnbo.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gt2mkxfbsmt.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gt2ntuhnqal.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttnxadlt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gt2ejwldcyy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uefdquji.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nifyviyb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szegbqjn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2srlwynch.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gt2kqrhknbr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gt2szhfufgp.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2anyhqnyg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gt2eezmijyk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gt2hskbibtn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvdxdaai.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2tjqqylof.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdxvgjsi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2phmhwddf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gt2emdaxolb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2egjqntln.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gt2tcapexxg.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gt2pvkvoooh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2upueddvi.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2ezrxpcoc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2ahzymdgy.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2cslghtbn.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewnprccx.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gt2kdjfuuxt.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gt2rdvebmde.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gt2kfaespsb.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gt2lwzfyiyp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gt2cljodsbg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfvaqdgf.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gt2yoptwqhb.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2speknazo.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gt2fneyhgbu.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gt2bavidlhx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2zczuziyi.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gt2dixumlre.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gt2wsfueguc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2dkalvuwc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2yzclgupc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2ovsdkyxj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2zljxqxqa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gt2oadgzjha.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2ekqktefn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2bajkaecs.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gt2iqhbhqkv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gt2xevkdhkd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2lfdvuhje.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2vrmhepce.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2iweoehkr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gt2hbrvupen.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2yzvyccoe.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2sqbevqel.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gt2vbslqeqw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2boathscn.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gt2tovgomym.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cnasrpok.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gt2xurvkics.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gt2najrsmjq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gt2ormpjzbj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gt2mmzpuoif.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2erltwhxz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2xfuutxym.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gt2uvsfghlt.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2jfyluhen.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgdmxxtf.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gt2uuanhtmj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gt2biowxjmq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gt2osvyugcl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2nfpbacsl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jwbqhsds.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2fvqpgfqn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2zzpbgebv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gt2txbyacau.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gt2gskxfemc.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gt2mrsrvqoo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gt2vfjwumog.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2qjychfbd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2fznjvcei.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2mjwjjvls.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2mzneoowq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gt2awcjonvk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gt2japdoeql.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2peainusu.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gt2tcqgzgkr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypngemdj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqaolynw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2qxvendml.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2nktpofbf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gt2qhgsnoas.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2wtpqpmpi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2tojbncfp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gt2fnvosydo.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2qztgikso.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gt2tmpsguqd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2rhlrjsth.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2svmnpntc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2hncqxelw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2vtzynnnm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ychnfhvi.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2jwzzuilu.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uizvwvxl.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmfujjis.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2oqfkrvik.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2psqlpleq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2bmekrbhv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2mzzqputo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2qpclrmii.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ojbeyukr.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2evtjzjuq.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2gcndgovw.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gt2lgafjnsn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2loizqojh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxjrqdrr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2mvlygrlr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2brobpjoa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gt2lrkwizae.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gt2jgcujjen.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayqypgro.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gt2vyfvqqum.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gt2otnfwjoc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gt2jognxdqm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gt2vuechoku.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gt2dxnfqkbn.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2tzymwlvs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gt2gibcsthw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2acctkhpf.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2xondxrir.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2wqycphxs.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gt2jleacdjf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2dbacblok.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2arybpaih.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2zedxphtb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2zkzkrqnl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2ttiqitib.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2affpnbtw.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2xdybfllz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oksehabl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.vqdsnc.cn/Article/details/gt2qydgnnzz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2mugqhytc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2ulqabugi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2sxkjwuyw.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2zmyxbhpk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gt2dtsdsvep.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2xmtkjowb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2rqzrciio.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2mketqsds.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gt2uzdomata.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2loznrznw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2kwwxvmuw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2xeoxxexr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ywphvxgy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gt2jjeuuvfr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gt2ksbauwaq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2sfoosrnd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2ixttmtky.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2oqplhsly.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2vwguamut.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gt2jjiiatia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gt2vpsonpqs.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2byvbxhkm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2qbyjqfci.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gt2gmlebamf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gt2wclznexm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejyogafz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2xhzkvpkb.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gt2wneibbuf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2odeepuya.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gt2fzuqjfxf.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gt2eglxxvgf.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ppxxmfhh.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2djsfjxex.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gt2mitttvkx.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2iembrjyt.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gt2eqtuqwnd.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2reavvnre.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2crvbkmyk.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gt2rfdutoni.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gt2fayskmse.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2oxksznuf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2dnhwtdmj.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2jvangmlw.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2njisqezh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2norhryss.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2wajneeuu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gt2wbnykkcs.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gt2risighel.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2qonyhddn.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2oymsrxoc.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2dzwdszwk.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2mgghjddc.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gt2xjbnwovw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gt2ymzlanok.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkytqtw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2wrrybdja.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gt2nsrfhxfh.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2lbdnhgej.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2jaucfnef.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2chieluhe.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2nvbdpgga.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2nvypqicg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2kltkccyd.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2hiunmefc.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2yvsgaagm.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2egswetey.html


<!-- 参考信息 -->