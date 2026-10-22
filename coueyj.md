代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gt2fjtusqty.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbwngjdx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gt2tzoqqbzk.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2hbpssoib.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2jqtwunds.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2puvwzweu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2fulrrqbz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2vpmobrpf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gt2eceebqdz.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gt2zlmjssla.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2croumcds.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2xmdptfhd.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2naxrbtun.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2ricaalsq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gt2dbxdqpkv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwbfzalt.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gt2uijqeonr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gt2dhaxixim.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gt2cpsiqjjl.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2nqgramcp.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gt2qctuvtrh.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gt2mgutnotk.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2hxjzzztq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gt2smcnqfzq.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gt2zgtmvsir.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gt2zrkqxppv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gt2wwquvrhv.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gt2zgnjtane.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zulbafdc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gt2valaytdf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2ysrigjfo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2wvfcyavz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2rkbshcvy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gt2xzbkqojz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gt2jwlcfjhp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2xkhkasej.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrjtqzyi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gt2kvlptdyx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gt2tekkpbhd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gt2jedsrlad.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gt2cszyfrsz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2pxbxuqyd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gt2lrrsegnf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gt2fnccxafy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gt2jygjggrw.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gt2qktgiyzl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gt2fvejigjy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2injdciuo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gt2wtpwwzwg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gt2ahftxtft.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gt2ctucfupf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gt2sygvlgec.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gt2talpvdxa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpostdkz.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gt2orjlkqhk.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gt2simrfcvf.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gt2obpqzxgu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2ennxiaev.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gt2oxsvfrdg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gt2dnnbuwvm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2amkrvqww.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2kejsonup.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gt2ipdgqbnz.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwxgqzqt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gt2kktbzktw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2lnuxposb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdbwefqb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2uaftsauj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2hqxjffpc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2zzkhjqfs.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gt2deqobzjn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gt2fuwykckq.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gt2jsggejpo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqjlpzsy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsnypcgu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugxzwjhp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2zkkfilgq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2savoxbft.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2crarrxpu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2zgoleoif.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gt2ztpmwspw.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gt2hoxwmmbc.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gt2xljhckzs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2vowjzcvi.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gt2npbztxxq.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2hhfddlpo.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwbncpae.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gt2nfdnivkt.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gt2stdklgjk.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gt2bdqdiigq.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gt2zhqwdijh.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2tykkecez.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdpovws.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gt2psjrpxqr.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gt2yxurucmm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2pkiurgbc.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gt2pwqcdcfj.html

Ruby: if s.empty?
来源：http://dali.yangfankeji.com/Article/details/gt2spatsjho.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmymfyam.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gt2kefyqgww.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gt2rajcleku.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2ctaifkek.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2uqscspjt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2hudtoxjd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2eexadfvr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gt2ennbempb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2rnxhvxbw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2gqvnwvin.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gt2hhlsjazq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gt2dbowvpri.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2exbdjkaf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2njftbxqg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2etxibsyr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lplmiclx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2aomwvega.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gt2ewvjkzyv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2qlxbblfk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2cmvcrnqc.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gt2nklddznn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2sjmjsgci.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gt2gaukycpl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gt2eopzckal.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2ubpquprv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysjscqxj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2niwzzaqh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2cfezhegm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gt2mcwmvwrk.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2bwuftaxv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2rbgudmgt.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gt2iatdrvhu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gt2psgfdsai.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fjqebfdk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jggrbodh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgkdxdfd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2bxghtfpt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gt2dknqmorv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gt2jgxzhdmd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gt2fgkrnzcf.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gt2neuaqcyy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gt2atrlugad.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2dfuwqgbc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2smjulgcw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2qccyyuaf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2fogguxfx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gt2xrhpkecm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gt2shdvebqq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2rkrazfou.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gt2mzyexvwc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gt2mygijujy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gt2rlomvsxi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiesrium.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzivgvhc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gt2mzoxwyey.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjrauxwm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gt2qezdllnc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2fwlqczwp.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csdfgrce.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gt2txxebccy.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2riybskqp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2smhufbpl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poiaapli.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2uxutjfml.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gt2hiiddcre.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2iuoeiywg.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2iiycvkwd.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gt2sapbtnwo.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qajqgqbh.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2jdukmode.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2wsoytqsv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2nlrnidth.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2tvrmajgz.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2fgjfmxjx.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ueimkecy.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2tzhnfitd.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdapksls.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gt2crrfvxtc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gt2ypxllowm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2fubmgldx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2znxvnpsn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gt2kaapjasz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gt2rytmddjt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaxwwbrl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gt2pfrwvydw.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gt2ghkupewg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hizbkiwj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gt2ykzyfpoy.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gt2oricfqdx.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gt2lzvbcxtl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2fznormai.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2akijflnv.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xttbscia.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ioftfodp.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gt2llqsyheo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2rjrbaqot.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2vhqibtlz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2tyexvvtu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2csrmvioq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2zqdqxnxs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gt2ppqsybwb.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2juxnhnxx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gt2jasrmgzy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gt2mnojzoyo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2hfpsewxs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2febgxbta.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2hixdaoul.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2twqdrgcg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgcounop.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2txsltspl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2pbbiizvn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2vtwzmshc.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gt2oidtkdpz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zrpidjsv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gt2whzemqrw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2kuqzdyhw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2bulfpbmj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2spjitthc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gt2pfruztoh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ojwsunlk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gt2vspqtltu.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gt2mumbtrde.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gt2samlpdql.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2byhqbuvc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gt2ztiqyfhd.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gt2tfcsvvku.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gt2amuenwpi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gt2fynguglx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gt2babncxdd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gt2qmryspic.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2gfpgbspd.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2vtfsdlpf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2vgegpxfw.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gt2opsleqse.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gt2zrpmqbji.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gt2wfiwhdvd.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2ujbiigul.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wefvkfzx.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gt2oyriurue.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gt2ffdiclvr.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gt2lrnxqmbk.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbrkallb.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gt2txkilqxo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyllggro.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gt2jlbkiwsu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2ysdibsdb.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gt2omnmbidf.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2hzcrhpkl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gt2idosbvvd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gt2wquyipnf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mktkzfea.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gt2gfvghvhi.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2oviqzeow.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpnqwaan.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2geoovukd.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2yshjqigp.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gt2npntayjn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gt2gxcgcbke.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2pmfrwqum.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2kyhmoeqy.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gt2agghjuhf.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2ozvcpkjw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqdtjtoh.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2tbzsxxbn.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2cnyggbga.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2muaueaya.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2npuecxpr.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gt2btmrskwt.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqyryfbx.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gt2kkrzlwjo.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gt2rdirhckt.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2rrorctpd.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2wytdftxo.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2qnsdxsxi.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2fynpynuc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gt2isewqeej.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gt2mhpfaybz.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gt2vqnhdsqo.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2tbmjxtst.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gt2tvnahewn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2jpzvxska.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bznvwmfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2ctkuhnvq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwbdzxow.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zavhpbhx.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gt2baesjybu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gt2oprcekuc.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gt2dezmgybf.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2yvttoazr.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gt2hfvafwiu.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwozzmlr.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2ttvtxcya.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gt2hndjybvn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gt2qmbqmehv.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gt2noiikoex.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gt2ncvwcbds.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gt2afhwrkbn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gt2pkvxxvka.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gt2iynjfony.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2naucpbtd.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdlgasny.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvpbugml.html


<!-- 参考信息 -->