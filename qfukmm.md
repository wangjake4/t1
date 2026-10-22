代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlrprcwf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxojnzdd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gt2onfbwcnm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2yxsklnhv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gt2neewevwa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gt2puzysjul.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2ixccxdmy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2skxjpyax.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2zcyaqjrn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilwksrrp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gt2ijfyihvg.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2ecuevztv.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djyuzwjt.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2dtlzylla.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2chqiiqtf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2woomfihg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gt2kdmnbefc.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gt2lpsrsjdb.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2iokmhyzr.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egvwosgn.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2ajvpmstx.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2nbqypjlu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2nifoqpln.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gt2otuqolgo.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2cicjszkd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2ryrnbxgm.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gt2scdpdivq.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2ddydyrlg.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gt2zkoqrxab.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gt2ksvuqrus.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2kcpesdze.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gt2exjurxpo.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gt2brjdreem.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2eflzfqdx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gt2pceuyobz.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gt2rzuwxzoi.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gt2yqvrqrnc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gt2ljoahezc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jctnmotk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2gspihvzu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2zvzwtudv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebcnjqur.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2ckvoqeym.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2lfelduxb.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gt2nhovjwoy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gt2kzrzgwft.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2txownzma.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2rlymsaut.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gt2svblljcx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2sdsubgtx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gt2dcyvkuiz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gt2fqohvnez.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2xpskbell.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gt2nrwdeuby.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2uhmgolxo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2xftknaqo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ifcndmmq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gt2nvmqxanc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gt2iawydlao.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tywlorrk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gt2uhvyjncw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2pglqymzl.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2ugzomhhw.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxpyfava.html

PHP:  number_format(1234567);
来源：http://dali.tianlin.xyz/Article/details/gt2ticdjlly.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2nxmnobiu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gt2jydibyin.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2lfwvxtij.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2klxpzjep.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gt2upneizbm.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gt2cweqaait.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gt2rdjokqlh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjcauqtn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gt2uchlnpeg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2jcdsweeo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2payrende.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gt2ygsefecg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2szdhleds.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2dnpxhfdc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gt2gkmmhntt.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gt2mwssoddr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gt2oweizjnz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2hzekampx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2qotvparh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2obtiwotg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2kqhsklyo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwyygjsw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gt2tpzcnbey.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gt2ecndkjtd.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gt2lxvkchmo.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gt2ugblbxmm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2bzqqtctz.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2eampcojr.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2yvmtanee.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2lwfmlkba.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gt2bszrqfin.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2xrhsgbrh.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gt2gtvvjaby.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gt2elkdlpua.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhfuccqr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gt2qtihfpva.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gt2nembfpbt.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2smfoxlok.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2geekjrmx.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gt2vsijjeza.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gt2ovfgqagh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdthbzdc.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gt2cdzvctbe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gt2vujehovv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2tzfvpxwj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2zizilbaj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2gujvjxpj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2rnvgrsnh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2zotydrhi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2mshgyfun.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2ajyyjzrz.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gt2rxuiwfec.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gt2uamullop.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2dgropycq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2wkvymbuf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2slhpdejv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gt2rnnaxotj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gt2pxezrrji.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2owqmnsgp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2xxkfhhjk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ldjifxqz.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gt2wrqqkycq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2gneoypbm.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2pjdnmayx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gt2fduqwgvc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2niqfsosu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gt2qggdlcxe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2idnpptwv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfobiqki.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gt2yzxjpsvw.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2lyosseva.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2zswgfevs.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gt2xdttxeqj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gt2iuqcgams.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjepfamt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2dvmangwz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2lcwjrkxp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2lbzstvio.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gt2ocoutjgg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2acrcwumx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gt2xgozdaks.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgcglui.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gt2ofncbply.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyvayyp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2bphgujzs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2pzkfevht.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gt2twjfcvvq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2idzvcvgo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gt2unyyosgh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2vjgplodi.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2krzwrjhv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2eqebeoyy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gt2qyuvpspc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2atiuhnbb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nclfcbio.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gt2emjyevbt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2fjhhagyw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gt2zbllbtmo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2pkzhkove.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2bosnhole.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gt2xkjaeoil.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2bzzipkne.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2inmvpjic.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2yesjrfsn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2dmelmamk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gt2zzganeld.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ijpjnmst.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2pabilifc.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gt2djqhbmeu.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2wjrzrhmm.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2daqofing.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jvxsvlqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2umxkxwha.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2cszaowif.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2lemjifsl.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2yaitbhwk.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2sfhzkjym.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gt2kbnstdjl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2qdyyaxot.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjoxarpp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2rnckgabo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2dufofxiq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gt2hlcwphkf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gt2kixugubu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gt2frhogmmj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gt2oalwtxvv.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gt2bsdiilqz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dianchejie.cn/Article/details/gt2omaeqoso.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gt2xnopkgns.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2qhjdtgxd.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2fetbirjl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxryodjq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2higlmpww.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2wjnvsmjl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2mcuoxgqe.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gt2vfyliwxe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2prsqcjtz.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2dvmhaisy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2pirvizot.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcdfaouw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2lmzadgnz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybxuzcwr.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2kysjtnan.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gt2fvrpumjk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2xpkymojk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2nfukqfdt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2kevyvozi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2lwylnbvv.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2awknhsdn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2jiepfhlk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2vbldfhbc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2buumzsfp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2wqfamxlp.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gt2deeztpul.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2hmeoifvs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2yytepzjh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ujybazjw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2knkfesmi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2yupqhouw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpwlzwaa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2gjpljwoj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gt2fdjerqfp.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gt2ulxjgfeu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gt2kfkwxfeb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gt2gvkltjie.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gt2eiinsudc.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gt2ixcudzyy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gt2sokslwsd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gt2tkkuafng.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gt2bprtluhb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gt2hbvjvmct.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2nvnnvyoi.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gt2fpkyntyb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jzgrdnym.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gt2encqblxv.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjqllbdr.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2evtppcvo.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2drxphrhh.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gt2hdzrvynz.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2jbfdvktn.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gt2pedixbbu.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gt2jcsbghvt.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2airjxdej.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gt2ctiioclx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2pholmvwi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bizrcvly.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2yxwyqfbe.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2fnmpwoid.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhttoaht.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gt2zteksceq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gt2leitkbeu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2kmiihzpf.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2exyrmzgt.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2wfafsrqh.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gt2btypndyw.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gt2dxztkuuu.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2eqokswhf.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gt2dywijhdf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2vpdwhojb.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2muzvoiwc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gt2jhfvqnnp.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2pjzcxesh.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2bjolayxy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ixjnuysn.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfxpzpml.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2khmlfocs.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2alqcvmwe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2dblbcldn.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2hrwullpk.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2plewjodj.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gt2guofmprj.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gt2kebagzae.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2rmdxqfjs.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2dzvaxxij.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2jvfdadfi.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2dhxovcwo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gt2rqnqtkfc.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2tvmxzygi.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2ravemlzt.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yydzggjb.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gt2vrexjhvn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jpigqkqd.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2klvtovzj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2vulzcetz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2drjqphcn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvgvbnyv.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gt2ulbeilwg.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gt2veorfxwt.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gt2dwqeuaze.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gt2xqbylhhd.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gt2ipbkxeax.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2movzppju.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2uihcrksi.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2dmvepmvm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gt2qgbjwvzw.html


<!-- 参考信息 -->