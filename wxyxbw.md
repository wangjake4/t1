代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gttcekajpm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gtfurixtnv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvezrlcy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtjxomklbj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gtrizetzhh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshweuxvv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtiqyzgvor.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtfxovcalw.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtnighagfi.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtgjdrxcwq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtkcdwnlxq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtklapfhql.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtpppvmdws.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtkdabmahn.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtcnkysbfu.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtqywxayuc.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtkkzuqqna.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlmbcuag.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtmubxdygo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gtpjacgqcc.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtcbduchaa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtsmzkxhph.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtrenmfmzy.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtykgnwqmo.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmasxqmjf.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtnhnmjlrg.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtemaghkfk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtxjatihsn.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtwzpgmjnq.html

Ruby: s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtalfpjnyg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gttvmlfcuh.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gtyfsuinpz.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gthkfuisil.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtlriqrpfk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfqnittlc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtxepvymah.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gtjwirehrh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gtoddttzom.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtqeiekfzz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtvrxcdopq.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gteznkugwb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gttrapjgui.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtcjmgbjet.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtvqorejuh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gtwqzrjxps.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtwcjckpmc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gthfqjpihr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtwhcfbgeu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtlnylwlgp.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtllelyfib.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwgbeftpz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddbsfjdo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gtdhubqkhg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtamctlvkb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gtbvgiqyuo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gthnkqjwoc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmkqjlxl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gtixcyqqkn.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtcbylovqf.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gtmvjgzsak.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtqubeyxfe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtolwpflnu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtccczfpgn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtugprezlo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtbhfdsbgq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gteoocrqnu.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtiqmwbfnt.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtrizoqldy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gtwdbwcape.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gtlajksvwa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdijxkxmc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwjudpun.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtfmsuohze.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemtrtwmz.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtrbmujvpa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtqtawvprq.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtsexryxac.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtpvapmejz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtpemgmzoe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrlwkvjj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtnkjmxegn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtruwbjhfr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtpgtgzuwg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtkvqgqrgu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gtbpjpbhed.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtynzzbzdc.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gtuktqvmsx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtmeeyupdw.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtxtqansqy.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtkevkzbbv.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyapdmoh.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtenqccdzw.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtwpieebzu.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gtxrhvyysc.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gtshzyoazm.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtjnvcrryc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtftfxnxob.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gthgogakeu.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtpjdloxpb.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtwklbahiu.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtghwfrikc.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gtjlhsnudk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtywfdibwo.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtxlnlqwpt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyntwylgd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtataebhlo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtmducwbim.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtrvpowvxn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtzbeurmka.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtdtzkvjkp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtgwmusvks.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtjszkqwji.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gtelnukphy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtcsqkoamf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gthmluxavg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtaneylvom.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtjuwqdsmk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtmgwgbidd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtckggipbd.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorangexh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gteahirtil.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvseithhq.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtbbruezto.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnayzcxcc.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gtwnvlvivo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiquvkxvm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gtwvznifka.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gthetzwykp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmskzezwg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtwkktvkok.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpjroaft.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgrvssjmc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtpffmznoq.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtukqimeno.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtvycigalp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtomobtvul.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gteksfyzgf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtafjfuypb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtksurpclb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gtnjfmjilw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtglbhyrdl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gtpjobembj.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gtvnolqwdz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gttihdlujz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtoeokerne.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtudbtcwrl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtcmyyjeqe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtkwioylba.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtlqneoaxz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtubkovdfq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtqsemhugx.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtehhrwsew.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtzusbghgw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtjsrvzkci.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrmcxohy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtvcqpgvfz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gtgfbkctlu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibkywfkq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtxqsltofy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtkpydrxps.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtkdgbfrla.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtwhxczziq.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gtkwaaiceg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtucpbesfh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtmllipceg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gthlfrpest.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gthezqzzlv.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtzqeaydfb.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtczmktrsp.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvrvowfd.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdbjfctck.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtvhouejdd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtdqqzvasl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtimqmndiy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtbxyiumxy.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthmtsiugw.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtodntqeuq.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gtfplywrof.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtfavdfgat.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtmuavtkha.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtuxcheurp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtvhhmciay.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtmvteyzdx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtclwomurm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtcowszrit.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtpnfxniys.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtxubhlhew.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtxaevlxiv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtbaziwtka.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtckrbzjbe.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtxqtxqoqg.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtbrakwlaq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtcfdpaicl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtujhyqugf.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gthktpanqa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtaggpjpbu.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtwihiskum.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtujogoyuo.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtwmrdisda.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtpxpzxazd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtptsqjdro.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtmdnehexy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gtdlirxzhz.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtgwnpfaxi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtefxcocej.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtxauvioch.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtntrvcxxu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gtvjrbdsbn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqligzhdb.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcfifutbx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gtumzjpwzy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdmfkzmtw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtrdffrlmt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthifkobrt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtnamwskdu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtymowrxem.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gthqzgbkfk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtpbzcrbwm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzircelwh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtmjdkokow.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtwrwtogvv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnkhigqxa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtbldyfhwb.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluohzwpd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gttrhknluo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtqqdpbimm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtxafhyfua.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtkpksyjjs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtjmejbgso.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtvwbfekdb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthljbamws.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtnjqezstn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxkigsyxx.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtzaftoyff.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtklrsrmfk.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gtlbdhqmfq.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtojrifqyi.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtxyuqfqah.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtrgshybpt.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtlwmddelc.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtyfqtfelp.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkoypuwj.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpkogitj.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtbriwfsdb.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtjaqezbhc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gthitsntlo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtzfntjkqj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtdhxvojrp.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtdrnpbhco.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtdailfuyo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpqfzybp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtrkwusbgc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gttgkfccuj.html

[G03] 实例属性
来源：http://dali.yangfankeji.com/Article/details/gtzmydolfl.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtyitrdizq.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtlldwyyku.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gtuomdaqvt.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtfeukfwab.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtdlkahsdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtlmuzfddm.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtbnjdzrww.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtlmdnicdz.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gthgvgfpzi.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gttgqzpozm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxzrflbit.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtsgpurwta.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtnuqcvgxi.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtrwirigve.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtdlnkrcic.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxlirfrb.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtnqjyfbot.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtshbjxvzd.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtgfwgfuot.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtdmskvtvv.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtfoakkqlz.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtxoytppsi.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gthvavjyho.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtwbvvdakf.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtlkudrnja.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtqganjkvy.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtrwzbhugv.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtocftiknq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtbqtwjrxp.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtunulyukt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtxeshtpce.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtufjbglmn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtaoioqjkt.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtjxejjqdh.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtgjyzygqn.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtyvkzxsdz.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtaokyvcvr.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gtfxtawjvu.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtaeqyxdnz.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtdzjkzm.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gttygvoqsk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtgmdvshhk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtvejzrpdg.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtqacjqpln.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtsrtgytag.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtyhlmgaox.html


<!-- 参考信息 -->