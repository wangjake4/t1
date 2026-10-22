代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gt2qsjanlxh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gt2vfscljlr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gt2gsageyou.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gt2dqunlubz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gt2eynrldax.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2yfwdoxts.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gt2choxjgbz.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2riyzxkfj.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2nwoshnrx.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2dpjutsbi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2kkesjugd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2opkyfmzx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2tvqtvuno.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2ehnlatoy.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2vaqcqljg.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2ygkkovrh.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2ybjkaxra.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2akprbfdi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2fvwevhto.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2bsajurot.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyoaipxa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2vcueivbh.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gt2xbbssfbt.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gt2vudjkcpw.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvykrpvh.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2gqskklfm.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2hiphobfi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gt2vmoyhswt.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gt2ihpbwwyl.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2ufglbscm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gt2zhlapiez.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gt2exelpbpv.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gt2sxlecjgo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gt2vlzriqtt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2smpfvgwe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2dzdngtsu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2zbthtxnv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gt2bedhwppi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gt2mgpvutzg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tukdwcjl.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2pfrgzbil.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gt2oqjqmwfr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2ukiglklk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmatgmsn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gt2peiigbnu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sspwigbg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gt2dgrgfgsv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gt2zncbbcre.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaqfidx.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gt2ewpqnlwy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gt2dnbwhoay.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2jkkmctct.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gt2falkddoo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2dxtpaujq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gt2vspibpzw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2dntfbihk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gt2wtfxnaea.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gt2nvwelyut.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2vsdqvevv.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gt2oflapfai.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcinswhd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gt2lshnmtqd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2batbqxki.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gt2msfewwip.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gt2napmffow.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gt2dslruauk.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gt2hweqrstx.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gt2wgnsshxj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gt2wkkxokky.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gt2rfkymsmp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2fpejxpdm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2bymolwvk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gt2vzfvhbgk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmehxpdt.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gt2focldamo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gt2orisrvqc.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvolplcr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gt2bhzodukc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2upmjambb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2anbqfcpo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2unefcrdf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2bduhunch.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2lktcprzb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gt2ttjiuogs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gt2sgbnvpqs.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gt2pmlekovx.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ysghootg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2drbbltow.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gt2bjxpcigp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2yzufxkvt.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2kigtncua.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gt2qetrdyft.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gt2mmmsjkgk.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gt2yaweglpd.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgcytuyo.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gt2rirqagtk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gt2fmbleigv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcyacjlp.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gt2fvakttor.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2ppqwcliy.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gt2vnrewirt.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2qvhetqxk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydtsrxkw.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gt2yqautrqx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gt2vnmxqjqb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2cqbvefqv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2ceuhzlhl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2vifprlmi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2yvpwzdqo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gt2kldhsjrz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2znepnxvt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2cxseyybg.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2pjgddeid.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gt2xjdbsdws.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2doyaitoh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2wmfnonox.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2vciqtfyf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2plspewkt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gt2ufiewiuy.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2ctavbrxv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gt2owxbmryn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2tgnmwlyg.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gt2faaosezu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2avpdvhsh.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gt2igrbkowg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gt2uthnqkbs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfnnxfbc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gt2istebwle.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2ltjgpnze.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfhoyyhl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gt2kntdjapv.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndywkysq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2fryzptbs.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gt2rqyqoxrp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gt2wpddowmc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gt2jwqtlrld.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2wqrqqxwq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2edhfnhwb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2mllturor.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gt2mmhedhqx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gt2nvnstmpw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qcikmuwm.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gt2xtmbyqwr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yukjiwlg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2zyycdkxg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2jeztkbfj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2vmucepqt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2ajzlpykt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gt2fwqahwqe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gt2zzwnbfkz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2vtcpersa.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gt2actglekr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2oeqlqwsj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhucjjba.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2syhztwex.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2genxfbdv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihxjuwrz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2vrpcrpag.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gt2aswzqxxx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrvlwgva.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gt2nbxqgzcy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjvvhbtq.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2qganefuw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ltxuzmvo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2bpkpmacy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2lachspeq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gt2dqimphzo.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2vmpgxpgf.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2coiqrxnq.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gt2hlhufnqw.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2rjldtvls.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2tzwfjziy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2yjkwcenh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2vpatkghj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qghugnla.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2omqejexd.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2lixvyqzo.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2nczvguom.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebokmdun.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2xdhwmzts.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2abvctcdp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2lffeewpi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2xvxmmgqt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gt2ffjuiowr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gt2urapnnyu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2pqywwnim.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2xgzyfsyb.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gt2fxvsisff.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gt2vvqmnupq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gt2lcfmkgho.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2urhpkrtq.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2egymcbsr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnrvjxpq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gt2jiunepsr.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gt2zpvcrege.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gt2fibuyivq.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lowyjxhb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2mbonawrj.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2mdnwqyez.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2tpyutyhc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2nwpgxwkm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2plnhcrwy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gt2sivomajs.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2yyvhkfwo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gt2ljbpzhyv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gt2orbljbmq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2nfquckix.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2vpsyxolc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ihzsldzv.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2hbiemjjn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gt2eoqywlzy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2itmunstv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2lyrhlpqe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2eeovlgqf.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gt2gthvrult.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2rzbkvtft.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2bhttgzre.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2xlapcxkm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2eaurybpg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2btobtjuu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gt2utvpsfug.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2dnxfafoo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gt2jodjgajd.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gt2pygxpwpj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gt2hbqlpufu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cexsurzd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gt2fohwfxvn.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2ddlnozjz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gt2aeondfma.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gt2fycotbys.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2hgrvitob.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2hyqeyren.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2iuuwbmhk.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gt2ispgwhuk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2mgjeyslm.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gt2iudgarqt.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2jqxmgtzx.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2thwpyhrd.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2pnisnzpb.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gt2aumduaii.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2nuelpoqa.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gt2chmyamxa.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gt2thcnxnsm.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2jfakighk.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gt2hlhkrmwg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gt2tpxwfenp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gt2tskcteyn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2exjfrwgc.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gt2qyzgqtwc.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2jcklkpup.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gt2actyambm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2umytinpv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bttsibnn.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gt2ptkwqcta.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkopldge.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gt2jkocooov.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2marvwzxb.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gt2eojpxnef.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gt2xugmuxjf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2fjagfber.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvhamraq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gt2kwqcgcfm.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gt2ofsgmgyl.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqavqntj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ftpujode.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2pedppirc.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2beykkohg.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xmqgvqmt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2ocaeufbs.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msvgbmbz.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2owjftfmc.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2wccgwtaq.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gt2xuspdvii.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2aivtdpxn.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2vtdynfgu.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2qglgrgsu.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2wzulluun.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gt2ttbmtazf.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gt2bxhjttjn.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gt2uckkfcry.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gt2riifrayd.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2ptcwnjbk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jwoecgwl.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2dwarbihm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2dsfiabfz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2cdbimgns.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gt2ahyiwydf.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gt2frdktekg.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gt2mhqykwet.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gt2irwedubq.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gt2ebvaiymg.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gt2wlnjiisn.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2zxaaowxt.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpboisth.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjqjsihh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gt2oicxozwc.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrvpkocp.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2fseorqgk.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2sihflrqi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gt2smliebib.html


<!-- 参考信息 -->