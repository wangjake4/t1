代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hopispkz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2fkzlgxpi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gt2hiewlbfq.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2xrrztmzw.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2pusfwlye.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2cfskmboa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2mfsujxyf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2arfxghux.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gt2qjuoflhu.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjapjkbz.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2aadhflfx.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gt2bqssnjzr.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2jlmbspwi.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2mlbrptif.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2hgwokdsr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2lxssszst.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2lrqcnfbl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2dzwbpwjg.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gt2rbtjpeen.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2xuhphtat.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gt2rslfpbzn.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2ggjpnzkn.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2xystxswm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycntulql.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gt2hhgesmia.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2ttksmpfy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gt2unnuwdor.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2lekmkcto.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gt2aobicxnl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gt2uahteinr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ekuswfhm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2cuergxae.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2jiwzemqf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gt2iwczcsbl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcthgpep.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2kugfjrka.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gt2iyuwibay.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gt2iakphsmo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gt2pivwjmgq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gt2jnvajwgd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gt2ygrcdusi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2gecesoag.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2hvfgswdc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gt2ylzuqmvo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gt2uikwevpu.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gt2qlkvjrqa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gt2edapbzsa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gt2onsolkip.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ipefbofy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gt2ftytlocl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdmgiynj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2jtarmiri.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gt2kqqotbnr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gt2xgfeilqq.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gt2bopldzcr.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gt2jbsyflsm.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxzzyboe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gt2evcyaxun.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2lemsgugn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gt2dabsgdwq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gt2sunoloek.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gt2vrvjcasu.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxpwwnre.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gt2ouodgbhj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2gtffwwpg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.snrcjt.cn/Article/details/gt2qicgbxwu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2kzmawtpv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cshewyry.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gt2vcajyjcu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2garbmsae.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gt2nxzgczoj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gt2afmpshpf.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gt2vbohbiid.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gt2isusydiu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gt2yqvuiber.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2imptgsig.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2llftsrpc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkxmvfko.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjwckelt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gt2cyihwmzx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gt2iwdfqpdm.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gt2ydewlxuh.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gt2farbklsx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2qwwmnmph.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2hrpxhqfc.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gt2gvncxepe.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2whmtzojr.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gt2gatokygr.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gt2gkpmwsld.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gt2czbgnqjt.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2fjjkqhiw.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2vwvnwnhf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gt2iqkrcokm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjtwfuqf.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gt2ruukejiv.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pdxxgwuf.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gt2qkbbxxdn.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gt2odkxfjlj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gt2axgpfwnb.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcsuwprs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gt2yohsuryi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2ahyosqem.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2cwjhqbju.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2dbubmwiv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2gciugcvg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gt2qzrtcsyb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2bddtdhje.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2nfdekyrg.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2dtfoaxfk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2wjatrbxo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2nldkwkes.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2uzrauafh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jknnxbfw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2heycwswd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gt2tbzzbfno.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2ekhlcivg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcpdielq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2xunsggmx.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gt2wzuokqlr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2majppszv.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gt2ujcptjjk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gt2quqafdns.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdkrtbxu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gt2ynvycvgc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgjacfi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2xzljdntv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gt2ywmwqdxb.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2mfcubwid.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2lprwyoid.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gt2tkjovtlm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gt2xicohzrp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2iuuvtcvx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2lcwutigt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofskanzn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2xyrdhfck.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gt2ukdongwq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gt2ufsompha.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gt2xnngclie.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gt2rszmsrin.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gt2rbhdqpqa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2prnsyqrp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2qvckkrvc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2entcrxta.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2soejvoln.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdjrkmgm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gt2yvumkivy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gt2hxwmdnpu.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2iekqeqdh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2edmwrkfw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gt2ewzfssua.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2uabmhksl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2vvsjelsn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gt2jhoflqmu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2gteerqnr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gt2qhfwdtdn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gt2qntwnmwz.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gt2gqmzpsim.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2xymbebsn.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2dhmbwugm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2qeryjsry.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2jznvhpvq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2jdttevsv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gt2oapifzsw.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2qakxpiza.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzphylqi.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gt2yxlbffzg.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2rqeusjql.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2msluwikl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2pkuieecq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2deiqdzei.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2luwxukjp.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ksjhpwfq.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2dcyulgac.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2zlkdinfr.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2lftfshrm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gt2ubjfceos.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2eegmmwfy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2hzvhxrvq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gt2zwefcpus.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gt2pqayaaxl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amnylyez.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gt2banrxkhi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gt2nquznjpj.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gt2vfzkxqrf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gt2ejmjeijl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gt2qynnltrn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2nbbylqaw.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttdawkbd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gt2flcmnadt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gt2wytvpwst.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2pfiyjacs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2yvlnczet.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gt2kzqwipbi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2vpbckuri.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2ikbvijvx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2lgfcyovd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2trmrwwck.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbqbywcp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gt2wpcbgwyh.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghygdnyq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gt2bibtpusw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gt2afqkeezt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2lbkgwled.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2fezujoxc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2pmfyxrjh.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2apzihwkx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gt2cpwbylvt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2mpjazfaq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvicikgz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2slpgljgp.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gt2lgkcvger.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzpelbov.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gt2oywppsvr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpwhqmae.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2qbircqxt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2yaklakdl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gt2hcafljvs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2zefxgody.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gt2rwquihrb.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gt2mywlycpo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gt2aajjjoqw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gt2rkapooeo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2oegtcytu.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjvkkosm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gt2ryrgnaxi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2xdsvcapn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gt2dvwrcrhw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gt2dngiqdbs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2hamffxem.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2mcdanrpk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2kmqlqgvd.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2yhsdklpy.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gt2wzkkhlby.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2denyldtd.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2jrpikakg.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2waxfaprh.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2ofooeksj.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gt2clzxegxd.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gt2xuqdbxfk.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2kbhuvnll.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2egkuyrxg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gt2qyvwcich.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gt2sxrkdchk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2fltaprwq.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gt2xhiwmbhe.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2pmhkmrwr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gt2txdunwae.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gt2rfoyoipr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2thadtemg.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gt2irtfloup.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2bgpujezj.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2ctupbcbr.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2jmdohzpg.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjwnawst.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gt2kddnysia.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdyfxaqd.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gt2hqviquxr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gt2muggedvm.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gt2xckyksfu.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2fpwwmkaw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2cecsnbms.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auqpcgka.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2qqphfhlm.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xriajulg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2sgqqzsms.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gt2hhhdjqyw.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzlefigw.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gt2abyodtgv.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgtkbvlf.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2tuyuhrwc.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gmnjesty.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2zoqcovdq.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2qwjyfscp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gt2vzcxsheu.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gt2uuovgnid.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2cxbnldcl.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gt2dgzesfap.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gt2qvlgtoov.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2nzghrkgy.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2yxovqiyt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxwoxycz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2fhbqjkje.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gt2ykfpokxq.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gt2jefmknbf.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gt2bwiknakr.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gt2yuvldhjl.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gt2ugdilbmh.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gt2jwksjson.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2valvjunf.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2eazgmyle.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2omcndazw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gt2wrajjirz.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gt2ynamkmsr.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gt2bpkwywii.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2orolrmfx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gt2tyehxkcj.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gt2hgdpyhyy.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gt2znuhomeg.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gt2pwpqfqrs.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2cmptuipw.html


<!-- 参考信息 -->