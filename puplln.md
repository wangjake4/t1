代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtddehbumd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtjmoacphz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtkwbddlls.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtzhktwjbd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtciptmobj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtinsrhbdm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gtbrilxpya.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtrvgnageg.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtnsyjtoxs.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtxrfsuswp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gttrntftnw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtxufgehpp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gtkcdupwxl.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtpvcikghn.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtggabysks.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gttgofyzbo.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtpscgrdjy.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gttbtlkudp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.meibo888.top/Article/details/gtfkkehamr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtuoncfpds.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtvemchloa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtnnxqpuak.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtmbwfssjb.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gteqtrkwhy.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtcitqrfxo.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtzplxcbxd.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtqmhvnmrh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtglnmhaam.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gtbbzcaldo.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtwwsapwmf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtfxwmxhih.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gturjuodqj.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gthtfsxoql.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtsgqnxijx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtkkhibujb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtdhdizjtc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtzijnzklt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtnqzhfurh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtyepcffja.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbzplutos.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtgofterss.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gtvyqqjmwe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gtgonewdic.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gtefldyxag.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gtqcqcfwte.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtlwepzker.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gtccusvmom.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gtdnrkxwoa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtfrbglcuy.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtxqdvyqoe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskvkhyzw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibbqkumd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gttuehulzv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtzajieetg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtszmxocmg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtddltyvyn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gtfylxseeh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gtsxmcyjit.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gtrymkxeim.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtlrgxompg.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gthiboeinv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtkpabyfch.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtsdjejdbr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtjmbvvtcx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gtlnsmsenn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtkiskhkiu.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtzbrchocv.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtpirvivsm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtvwbtdqpj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gtwcmkuucq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtamnacwqt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtvslmaqxc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gthvkyncez.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtsahsvdlj.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtxtmdxavh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gtftdqcehe.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtsbfnnoei.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtodjrcwlj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtccwxhpvm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtmjigzmev.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtmaxgnjqv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtuxwjchya.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtdgnuexjx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtapfweqwb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmrrhptt.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gthlkxgkcr.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtsgezbmwg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtrdeflqqp.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtilopkkgo.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtchakwxna.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtbllcyckf.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnhfrczj.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gtefmvdgpr.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxnqhimv.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtgqgvddzn.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtgqntqwjl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtorqfrthe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gttxzqvgeq.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsjzenxg.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gttsliuacr.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtfttompdh.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtzqxmkzgo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtkmapelrq.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtyzlqygwl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gtxbpwqcue.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtysqabfmq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtqxmwcrju.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtridafvtk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtjevrpfeq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gthkhelwlc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gthgtpxjmo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtalvdaqqz.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gtjgbwafsi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gtqvjpqyjg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtzllkcunu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtriqwytth.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyarrwix.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwugsrenu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtovdqnrgg.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtqpaoouer.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtxbsgzotn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjsheibhc.html

F. 文件与目录
来源：http://dali.sxryk.cn/Article/details/gtflijleja.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvliqraku.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtxbvmdixj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gtnaiotipb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtwumonkpe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gtvcnioacw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtvflpoufr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtjyhtnbhf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtxhlrxutm.html

Ruby: File.read("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtszrpqbhn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtglkfcqav.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gtvnoexujo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtlnbrqyrk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtemzjhbrw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtcxixrewi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjonetarx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtemzjebqv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gtclyjifna.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtpsdukbrj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtoznldrmj.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtwcekbpxj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtbxvrvusj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtmtlchtcy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtumjrylmu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtfubozbpq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtrurgujmh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtrmkxoecy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtvueaejtx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtdrailsfa.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtihzuyqzx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtalesyrag.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gtktqdrbyk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtzouzjapx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtesmljybo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtmbyermcz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gtucttlvox.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtrwxqpndu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtdwfcdmnc.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gtgaknvboq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtdtyquzrx.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtovanrzmd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtspukpuet.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtdflwsedn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtolathgco.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gthymfsssu.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbaivwupf.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtfeoknhhb.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtlussjzdb.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtffyskkjj.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtizsuiaeg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjntgfcki.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzgetzizg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtqqwdhvoq.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtykcjyvhl.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtaltbpyry.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtxraffkxg.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtgtecrvyh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtpdqaewhz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtqlnhgual.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtknynuepz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtqdoeebkv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtggcknvax.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtpjaonftt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtxymhwrju.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgholztl.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtjtuwtpry.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtwjzynelh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gtiuzsiamo.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gteqiuhwgp.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtgxtnncwt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtvxpqocpj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtzcfhgoqw.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtymztwgbk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtvngknhph.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gtdfbowfpr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxazmweq.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhmzovaw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtsppinbuq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtahbjheon.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtowyxqlue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gtnebtaiql.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtsfeeecpg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtxljsexls.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtucvjizuc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgdhfwsst.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtosqqrqes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojfjdtnl.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gteufdsjrq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gtdlzrlxql.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtdnbypdqq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgtuxyebf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtdsfsbaes.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtwcuopkzu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpvdfyxrf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtnvrroifv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtijiswuay.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtzurpkdxk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtwcoavnid.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtxycsvbaf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtgjktfalg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtntlbbzmb.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtcviagffy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtoenlfonq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtfdiglmxu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtinucjgtf.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gttlucxpif.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtbhkfuqrw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtcetuvxfx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtsgrbplan.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gtnungtpma.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzvecchzq.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtximysmjx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlejspmiw.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtahhldwbt.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtgltzycpa.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtovmytarw.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gttozqgfua.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtvlxyyctv.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtxlftmkgb.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtjvvsurhw.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtpqfkchlw.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtvqwkoffm.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtlviqsrry.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtvrltuqjt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtpukwajsr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsnflzbn.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwjorjzkj.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtzjwouxat.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtxukhenmm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtjwovryhd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtljwbtrbp.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gthogesbfc.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gtnpiapxiw.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtcdjalcmr.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gttutmnxwa.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwecvhhz.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtndehdpfw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtodbmmmbs.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtbrnjypzk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtltthlglu.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtsdojeejv.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtstqvhrly.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtybwlzpry.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtusprtuzq.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjnxuhqm.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkuxgvkay.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtxfzmtyys.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtogjrlapk.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gthaoauaeg.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtnslizxct.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gttxogdfbv.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtokfkdwvy.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtusfiurvf.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtzfqnmaaa.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtdpruggcc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtzmszfbbv.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtrewcjlmr.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gteudlitwl.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtjxdnkezd.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtqfvaoeix.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtligxadxy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtexryawxc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtxgkdhhor.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtcuhqpcyw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtwpbvwcnz.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtyccxgsti.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtdzjuykyz.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtircnjsox.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtmuvkeiug.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtutbvdnmx.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtajrpllsg.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtgjptzxcr.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtfzjvegdq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtazhyduga.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtqpukaoro.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtmjpgpsxg.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtccjiuyks.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtewootvup.html


<!-- 参考信息 -->