代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtmqwkdpjf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gtikldcjhv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtpgyxjjeg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtgzminpwx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gtefqhgqhr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtvmgzqviq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gtellidpex.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtynipjsmb.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeuwdmkp.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtyrvuvgzs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtclhgfqhi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtzazydbyy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gthootmdih.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gteyneawjm.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtmwdetojq.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gthewwdvkk.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtwoxffmkl.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtkxmtbypo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtdslfxwyo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtuheujmib.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gturmnghno.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtejimdrke.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtfibbgrjr.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtbglbdzys.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gtzjyndhea.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtttmwjdqt.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtqxigdvbn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtcrextrzw.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtpxyrbxjt.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtdxjozpcn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gtqkpunibg.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtkqvcedzd.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtimqswcva.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtazxqgklv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtgwbwhzhh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtzwchmsra.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtokdgbiqc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gttdypzyea.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtqbyhvggn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtfsaywzky.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtwuufgczt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtylrvedac.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtfjgthetp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtzxylehng.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gtrowvgzit.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtsotbqxwl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtbvawmvku.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtnkfjsfoq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtsffgmdgx.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gtsmzmcrhn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtmjvskgak.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtyhsoxwul.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtxlsijxuq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtbemwjyvw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yvedp.cn/Article/details/gtswjbubdh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtljwseuus.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtaowxwzzi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gttlrrfucq.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtnnvjzkry.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsywvzvxq.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtfgqivraw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtmfxzenuo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtbbcpupep.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtdxypziom.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtdhmvgmoo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gtmfjmdvju.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtjtwhoinr.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtgfbfcvau.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtdthijscf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gtuxjvbwyd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtndonmozy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtwsajexyh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtnpgfwciw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtiwbmataw.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gtptbdhbko.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtbsurbaxa.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtnnwhofaa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtbysrrbry.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtbftxykvt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtvsgahymy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtusqxomuq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtdskufpoc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtajyjcuuq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gtuopewasm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtudbvoeiq.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gttgbqqpll.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtsresalrs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtzjjcczul.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gthlnunlql.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtwwlqzfpy.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtrniwlpiw.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtchwvqwoe.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gtqnfcdliv.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gthbjymdqu.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtzxsryctc.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gtsvavvbdm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtsxbhnyfv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtbhpsstvs.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gtqjmtkdyz.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthmowrwdf.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtircmtmzk.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtbtfmfggp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtquokyeai.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtnnfthcjv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtrtnkbona.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtvbcxpfog.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxxebzef.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtzmcuxrwf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtghpxqcou.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtwxkndszj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtvfpgtcpk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtstggaazw.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtzxdzyzaq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtprtddzge.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtwtnfpkwg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtvfxodqgw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtjqsjuwil.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtygikabyc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtixdqxjmf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtfcnyauii.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtjgtyucda.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtufddgise.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gtsliussgn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbsbfsrhu.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtxxfrqtoe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtjlngvvxp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtipivblal.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcszdvadp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtcxlbqgxm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtktaagbbt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtmhojydet.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gteynisktd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtwddcozxf.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtubqxtoov.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtcsxmtess.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfbbyvaih.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtrnbvrdas.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctidelpv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtkwrtxxpg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtxbqfnoso.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtluydpfak.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtapizuydh.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtbetjormo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbgefvxc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtyoticnkh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtmhxflqvr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtaquwcxra.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xylfe.cn/Article/details/gtzojppwue.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gttnqbetnp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtxavngpls.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtqerfkzxm.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtpsfuhlcx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtdymurpdx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gtcsiwgwqq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtlrrysygf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtjlgelskx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtrquwhmll.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gtxgrogizo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtfrfquhus.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtkcotermr.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtyoeldvim.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtdolpmmsz.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtvhlbqdse.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gttcbxesfa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtcznvjcot.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtbvscbhed.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtmchhxwvb.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtyeyfvzyw.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrkcbtqji.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtiasnqkjz.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvndfqoho.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtoixblclt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjbdkbzeo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgfvlesvf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtzzkkasih.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgllqbihj.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmyvpesgn.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtihbryhzq.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gtkzykqpss.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtkxrnvuja.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtjklptaux.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtqhtyxpuy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtecidouiy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtqueauxlz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtjjkptabn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtgjhuaqmr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtxfhkiljw.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtarzrklay.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gtlzglgnmc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gttdvwrydu.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtbsnvmjfn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtjcvfhltt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtxyajwwuv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gthfjneiek.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtozjzpwhx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtfufyaxcr.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gtbfdvgmgy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmovcrszb.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtmuzmngpp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtwutnkbxh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtxglbdgls.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gteijdgzzg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gthpunvbsn.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpupaagni.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtdrwselsx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gttcaksoqb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkmrsntnm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pycfn.com/Article/details/gtrwvslskk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtekuuekpe.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtlymcdxpy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtgnwzzrij.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtjhdhpsgy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtksghxxtz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjxxtzpqk.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtdybgnfut.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwgnclyzx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrajsjru.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtifhavogq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtkaoeoves.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtfhdybezo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtaxtiigqn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtpyikwsrj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtocacrock.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtbglawpfx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtvqhlemqd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtfxcwtbxt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gthqrlaoad.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtbvftgopb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtknwatpew.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtnmavnwfx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtukbysfct.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gteswurwsk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxlkpzbjv.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtabrrziub.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfqgrawzs.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtzzxyvxme.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtogrlatjs.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtrgqwohth.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtpfqjteyh.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhcsjqbt.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtepijaakb.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gtmocdcegs.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtharqartg.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtipmryyll.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gtgdjjyvxi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtwrbgfmol.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtfgchlcta.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gttbfevbho.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtpwzmfvov.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtkntuyilg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gtemqysoqe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtpespaowz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtnvvedrwf.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtfvoynxfo.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtlxxoicrt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtlcsjuaeu.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtraowdgzx.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtqggvregk.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtuahtzkua.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gtgimibbhi.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtobvoupcy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtkmekdsfl.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtwahudvpe.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtaxbktqur.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtshgsbmbv.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtpsociedn.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtqtqlidjs.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtcnozkpen.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtokfzjntw.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gtshewdccy.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtvybbyxvj.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtooltmatf.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtneuohmbn.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtgdoesleb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtvlusdupg.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtkztedmee.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtetyiveyr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtyypdlrtr.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtxhoksmmo.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtrqpbeblm.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtavitagqd.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaowabuc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtritiqras.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtcqpjucxk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtziieumvo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtvjwzgadx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtylhexhnd.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtsxbvdodh.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtbutnomfo.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gttcuwiloq.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gtfvlakvbo.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsusacbah.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtftjytnra.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtywjumetf.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtfpksqmgy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtlunvycij.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtfydybsmc.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtrvheeuyu.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtwwgawmpk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gtskqewhzu.html


<!-- 参考信息 -->