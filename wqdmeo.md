代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtupiecvgd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtyvdwygtr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtxsaqvhvz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtajduijcg.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtkhlxzwqo.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtjdocoqfo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtcptedbth.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtjowctotu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlekxftzt.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtikfmbnla.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtikcorxee.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtzsrhvdnk.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtjsdcidqz.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtruegvjhy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtqlxruysp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtqupbndcn.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gtntmlqeax.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtusclqrjj.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtxlgqvydg.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gthpfzpoqu.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtkuinuaav.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtpgtejyrc.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtggxozsun.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtyvnajvli.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtqchifuhy.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtskfjyriu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gtzeyenjkn.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gtowryxkqz.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtqsczurbr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtqoijwajb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtdlntzirj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdwfipbne.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtromxkajp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtlkdcrucj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtbccdwvtp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtfbrqmucq.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gtgmresmtb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtvsgduznm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtuomgnzma.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtyhnuwkfk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gtzdczsmra.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtcixrhufw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gtzbgvpdmy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gtnntedjrx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtltqcopxq.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gteazirjet.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtnhuqbrva.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtelbrknkv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gttxqmrvds.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtcixbmgja.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtpnvvfykb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gtcnliwjzu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtjappszsk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtzrsumcsy.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtesmhaaxx.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gtlyaclzjd.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gtauovgfxx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtezmmkiid.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtstjxtyah.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtpvgliglu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtavwrvbpz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtdphsmisq.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtujkxmahw.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtdqcsukxh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gthmbnirlv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtzfwsavdo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtmsjktntp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtutbwrwvx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtcmevdneu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtdbnufcla.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gtzqxedzkf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gtvdsokrvt.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtwsrzwgdo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtxxabiwob.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtdrfbdtgq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtdcapmnmb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtdlfbmplk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtsxeqnpct.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtnmizfsno.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gtiqrfuthv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gthjqnvbht.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtdomgjebm.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gtdxjgqznp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprpetuoj.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtaxucsuro.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtaxubnxfx.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtsilfpdel.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtiqhqktoc.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtrfxbdndz.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtppxzsipv.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtugcvugfw.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizlriwbx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gttcvsortv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtsrvukcfh.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtipxvsaey.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtclmauson.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtgwjbnggq.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtljkqvvyh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtggdwfrqk.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtkwwvpwfj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtltwdqrpk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtrytimfbk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtebqdzbdo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtacftqrue.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtrxkdwtho.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gtaflnpawn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjneglrlg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtrknxlfzj.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtkpbviwdk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gteinouukb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtkzsvizhg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtllwcgizo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtlpoplqyd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtlfevywuc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtyigtclfs.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtfgpdytem.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtbecmcwmy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtehtvltiw.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfmripoo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtolmdtgxv.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtwdcanqoy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtwdegaqnh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtwunulqtz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtoaknsqkw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtzyqyipdh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtrnezvypv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gtttrxgdpc.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrsxmlyim.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gtypkoxvhj.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtuhrlhrbj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gttwaqrpdm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtqqvegsml.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtzovjadqe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtnwkfyxbu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gthwfqbeqk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gteohnxmzo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftfycnya.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtjkxxdaub.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gtjgomwbbn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gtqooksmpj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtdqbbcgrk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtvrsddhmk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtholdeicm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtfjkiuccn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtlfopxits.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtnebkotjs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtmraqkflu.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gtsquduafl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtlfbakcml.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtvnmyguwm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtnnimyifp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtzcjbpqml.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gttqliudwa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtmivpnkjo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtwoglhqfb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gtbpwxrsyq.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtdsjjsjdn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtfdsgnejv.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtfgkkgyvr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttuynqdnr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtvopdqdfu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtyqecoznf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gteffvkeio.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtkoxhdbht.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtamkpolwg.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtizmdljdl.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqyggciwu.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxgqmizd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtxhzzviln.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxuapggte.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtcbejblgo.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjmjdigea.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtthsgfzxq.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnszqqfaj.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtmzgnyifr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtjbqwxdds.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtktpjoiit.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtmeiykayw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtvfuyhttn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtsaqtrtkh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gteiwnwdpj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtlsecjplb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtninjetly.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gttjzjessu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gteryecolh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtklpdvuxc.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtanagdpos.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtfewycdqb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtokquwlsq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtkrkzsggy.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gtwodtlusq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtkcxbywvk.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gtrvlmugnl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtoydkkbpi.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtzxyrnecg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtgwibsoiu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtdccdvqrg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpxdgnbh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtxgbijjwn.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttreksnym.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtnvkrnjnb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gtstpvxjic.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqmfrggrk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtppxqvvlw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gthggpaqbi.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtfvlwvovf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gtydignrkz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzraekcft.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtehqlqshs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtyidziyup.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gtjuillqdg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtrppgfrfs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gtxncnpqcs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpmpqrjr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtyajuhbaz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtnnzzpuzg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtsdvlkwrl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gttcdsuton.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtdjtftyyw.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtvqtyforj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtxamnfupg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtpokzlamw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtefltrsdz.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtwfptzluu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gtcfoukbvb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtltkrmuvs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtyznawqto.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gthjrfrudh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrbrxsqlp.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtldpdfpfb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtncihomok.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gteqouehib.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtszclapzm.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtstsokbbm.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtnxepxpam.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtyxlpuntb.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtmntyweyr.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtyfybblca.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtkikmwslh.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtruxmijfd.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gtsxpsezfj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtwjnkjild.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtedwpsdut.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtuxjaccka.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gthrmrlavy.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtfrvgwyva.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtziqxjueo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtmtfxgoyj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcepsxjxu.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gthmfixhci.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtmqeeambe.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtswaphwmu.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtrkqjqcbt.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpcycmnm.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtohvliikd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtjvapghck.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtamvhncpn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtnusmpdbm.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtgjujannx.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtpwlmihhn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtxtdystss.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtvgnbxldu.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtufhhnpbh.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtegvfqltg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtxwofkevf.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gtrqaixwnj.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtgxklmcmt.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtrgjbuprh.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtdtxmhppm.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtufluuaur.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtcugxfzyf.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxbxrgiu.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtzulhtpwy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtctjshxvc.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtzbzyjdsk.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtoleuhpnk.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtvgrannak.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtxedhgzzs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gthvlkvmcm.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtvqpqzxri.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtiitibmei.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtiakiahtz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtdjkldiil.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtpzsmvikn.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtipunimaw.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gtvtbcesct.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtorlfsfil.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gtwumkeacd.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtywiwhklr.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtgxdutqyr.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtkpehjbxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtjkfhvhkh.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtvmhvvxfv.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gttwhzblxa.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtfutfobua.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtfhpumher.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gttbjrlhsa.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtomxbuvgm.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtpmyqigks.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzttefkh.html


<!-- 参考信息 -->