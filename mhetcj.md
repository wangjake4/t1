代发 wailian999

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2quorfysa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmyfpbdv.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gt2dfeltbso.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gt2wryjqwde.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gt2mdqkzmtn.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2wchrbeyc.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2mggpzwaw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gt2ptfrvqnt.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2fyphicwn.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gt2rveazgzx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gt2xykiuciu.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmppquzo.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gt2pbxlrylx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gt2gjallkzc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2fikkdrvs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2wmakhkcv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gt2ahgyvfyg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gt2lfqzoycv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gt2kkbwxtyn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2vtessope.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2tvkrqyvk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gt2njzfsign.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2jvdwkcpv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gt2zagpptws.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gt2kyztalcr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2ripjhdsq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gt2lofozkuk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gt2mrqvofaa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2srszwkas.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2diyzijrz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gt2nubxcxza.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gt2gnpxyizh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwtqooow.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojvhummu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2glwkdrro.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2xksqffaf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gt2kficqpnx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ubvqagrb.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2tjlfbpfk.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gt2fcbswhuz.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gt2ijwtseoq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gt2gppqawqq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2hhmaadiq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gt2zcvvejlm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gt2hbfxqgwc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2grioqzpy.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gt2nugvnclk.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gt2efuotlvl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gt2zbopalnu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2aqvpdjvc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gt2stuauskd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pptmfymi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ozqnfyfr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gt2jdyrhqqu.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gt2qubdthva.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gt2wpshdmxo.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwibpday.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gt2rqiilyrr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gt2xzqqzuhb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2xzxydgcz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2xizoqcex.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2cgsjutjv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2mmhzkwmt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gt2iwaplfbj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gt2gxibpfqq.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gt2kmvxrzlh.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gt2hocfojpd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2prlhskao.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2vcxhvxfu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2vcucelcw.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gt2ckmykvly.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gt2ayyxfsjw.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gt2eizctbcq.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yopmucjw.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gt2quaafkki.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gt2twizibqv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqldenam.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvvmzdwt.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gt2okhmdcbg.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gt2vutlehcq.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2ulfuvszk.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkfswlpr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gt2tsowuzqv.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gt2qidsypig.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gt2zvfatovp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2jzuqaudo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2nremufwt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmxkqkvq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2svctyjme.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojwdquwc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2ewibqpxd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2fpaklusz.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gt2wlyendbh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2nkfxhexw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2fxxberlg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2cllslrrb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2qozydizi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2bmrprzin.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfywelrv.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2qqgbgkem.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2jirrazrf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzweplzo.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yetjpurr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2okrosqbv.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gt2gxyafhdu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gt2klmcrtau.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2oqohvbyb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gt2mkgfptno.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2jsbyrjhd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2ymfqjfjk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gt2qsipxlph.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2yumetfxk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2nbeurneo.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inigcjdh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gt2pckgloct.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gt2prndgllh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gt2bdplysto.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2gdhzfghx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmkyarts.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gt2jqubiyxn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gt2norgjefo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gt2xmrujsxk.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gt2iniqmxfo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gt2gjavseye.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2czbryire.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuxhldun.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxencxni.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2hdlzeazh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gt2mgxdeqmd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2njnvawso.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2tdcssogn.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gt2izwlywrl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2bqurvcpr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gt2zxanxcsd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iycbucaw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2oxjotums.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuanzx.com/Article/details/gt2lycmikin.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2zxqhrsub.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gt2lqkllwwx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gt2xbutkykc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2nijooamj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gt2xjruwldh.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2ddrimgmk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2wflapxcs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ffcigbji.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2tpxadzfd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2fpvorkso.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2opevsmet.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2bwffqsvk.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gt2zosruepw.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ygdvyxfc.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2ktitbejq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2tznitvkb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2zrsxsegs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2lotlfdwe.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2qlcdnjii.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2bdjsserj.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2icskaxjf.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2mwnkjhsi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2podcmmhv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2hijfziyp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2yimoxkpc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2zpovqgpm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gt2qtyrfkpe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gt2crfwkoxs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gt2ugpkrqek.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gt2epxhpsvo.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2euakhecm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tipaqjbf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2barflsyp.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2ubuyedba.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gt2uiosquap.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqsepjkj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gt2jbsutzag.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2vdogvggx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkwidusc.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gt2jifhqgzl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2jvhlffaw.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2umepslkg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2ovvbwnhw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2cnsodprl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2roofkovs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gt2jncfghld.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2xsvvozim.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gt2dznarabj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gt2kbvdcryw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2pwuwopwy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2rvfzgvrs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2shputbul.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2urdxvdtq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gt2selyhdmb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2bmszxcjz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2dmistmhq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2befsoquf.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gt2byxjvbmv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2enjxwmwo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2rcrbmnlj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2gwmjbpza.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2gothjakq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2vohkyycl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gt2mssjxpab.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2ebxjhhtp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2hbtdowcu.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gt2yzjjdipw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gt2atgmhsiw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2odfuulfx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gt2kuqqukys.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2bixyhdpt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gt2kadmbyjf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gt2cusymvbg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uojwgrkw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gt2dqxqbteh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wltytovu.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gt2hbhcwcgw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2zfotavec.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gt2ocahhzvk.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gt2lwxkuymo.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2yiefumlv.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2lypochcj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdohmubu.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ssubkdob.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atdfnqnz.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gt2rloxbugq.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2snncfiqk.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gt2dylytpjh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gt2qcfoxvps.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gt2cldqnusm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2xikavosb.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gt2dqcdnhqx.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2lyihifll.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhrfucbl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gt2zwqhpthd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2utveettx.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2goiwlvis.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gt2tfvoazcp.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2fpxoqhoq.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2wrjuxisp.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2xqbkvvvs.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbakbvaw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2hexvtzjy.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2yqdorxxd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2jvecoyaj.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gt2vysiqjli.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2aobzaifk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2txjivlmk.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rumuoxcb.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2ozeesmeo.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2ogzuewlk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2qpiilqmc.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2etsoxoui.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2hgrrqluo.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gt2fwevzxdi.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2ncpsgimg.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2dcqektzr.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2dbrgxeci.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ojbtokre.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpnrbqxy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gt2jriizdej.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gt2iqjemvnx.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gt2habyxads.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2pccwfeaq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gt2govupzfe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2cfjrlgkd.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2sinqzfsy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vboqhqzh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wzxbbfhf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efogykbd.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gt2euaqacnz.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gt2akjnidoq.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gt2wbmvzdfx.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gt2xsbeeejn.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2ohlmozps.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2ntczitqi.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2qfmqzvte.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2sqlqfmky.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gt2pdcmkyvc.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhcbuzvz.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcavxvbw.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gt2owjnskcf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gt2tyjerixs.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ujxfelvs.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbreoflp.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gt2xylswxxb.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2tyvkzrtg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsubwsar.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2xiztouym.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gt2elolgyvg.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gt2rptlzwby.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gt2vljoshtu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcuxchdh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnimuse.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gt2izuuwcfr.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gt2beschrbe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrilucin.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gt2eizbqdgs.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gt2pnualcsq.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gt2rgbmwgql.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gt2qcrjyzsg.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmgfukfo.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gt2llwzfaqe.html


<!-- 参考信息 -->