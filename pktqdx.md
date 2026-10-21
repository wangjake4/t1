代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gtugowyvua.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtxuurvyee.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtxcwteuhx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gthexyrbhu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtclbskilu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcmzvkby.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtxwpdbmwz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzeqiuqo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtiskjkmml.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtamituhgc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gtqusukvjs.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtvinxutil.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtfxlzyics.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gteozasghf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtemixrlrq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtxsiaiavw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtplkahnsz.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtfodouoam.html

Py:   s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtltnplbcn.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtqoubacct.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtxvxovsmw.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtqrthpejq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtrgfcfbsx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtnzzjctcx.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gtehnfketz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhepgzrj.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtdofnpypd.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtxnuqryjj.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtksnobsvc.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedebkvia.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtyurasroh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtsxudeend.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtaoerjxcs.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtlfhwhckm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtwzuehock.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gtrbgahoda.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpllvvlnc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gtblbgpfzl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gthxplgfno.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtxmupkmyk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqavjlfnm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gtzwqcdgca.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtuujcnftq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtalljxado.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtxqgunuco.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtalsbemle.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gtwckergqo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gtwfadpbcw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtsytbhjjm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gtebqijktl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneoaloqe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gtbonjcmwb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gtnqxyqkbv.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gtzhmvfofv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtgahypheq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gtzufafqqy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtojhzqejl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkkgkvqd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlthvdzvn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gttpjxldiw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtydaedmrc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpniappoc.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtbwbwsqfi.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtoyajctfp.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gtjuiqaxcq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtzoqigtoa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxlsekxp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuslvaxrq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtwluxscqt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtuvdwjmte.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtphweqihi.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gtrsodfmsa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtjtdekxrl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtcdzuqbec.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtvotghahb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtfcgjlfxr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtnwuqptbr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yvedp.cn/Article/details/gtxlnrzgrz.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gtysgdazht.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtcefjskeg.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcmbvtwu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtnrelndvd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtrlrjgaky.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtfwqpenvt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtbuoaohnu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtjcfzneld.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtafgcygdi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfyalxyp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtjetdidhc.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtonqzfhny.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gtqckuqhqx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtinthharx.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxluwzyhs.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtsrialovt.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gtkigwvxlg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtmrgfzyzx.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtdfrfyezm.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtteszhkwj.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtmhcellne.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gtsqqebyzd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtvzzverpm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gtwktidkhs.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzunwffvp.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdusknqmf.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gtnztnhsxa.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gtyqeqmzob.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtighnqrrb.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtvldhwvsa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtoshsjsfk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtgkyblxvn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtfgpiaokm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtitwjoghx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtcbbyypet.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtxcpwkcyd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtenmbkqxd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtyauficqf.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtblxgdbin.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtfwmsmqvs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtjjqgxpfa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gttxdeylsu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtnmiyrrrj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gtftmmslfs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gthlidtjkr.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtvesugulq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtrwqnfzcm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwirtgltk.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbywnhmo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrdvficpf.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtnbtpghbq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtjplaqoiy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtggsvpdpm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtpeyixqrs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybpsdavh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtjvsbjqvx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtujbobunh.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhxlqzzy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqqcybdzc.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gtirfhpalb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gterepybbt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtomncemxi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkbzoocty.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtspvposaa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtwsfmtkyk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtycajbzra.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtzzvifikf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtvgjnthzi.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtmndbsgtr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gtmazxrbsg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtzzicnlwk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtfwcbzjaf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gthrirepeb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gthqlxoyiy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtjlqqkebg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtznlpyoyr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtvxrytyek.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtphxdajrv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtqtwjwpus.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrllgrck.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaentfvlp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtnrhmmiqi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtxcntcmpg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtqjltroek.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gthzuaivnl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmvexpkf.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtyfppnjst.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdiyumnz.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtdvinvziq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gturhhzcjl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgkdigypa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtefwnytfx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtcnixkvmz.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtapvzbnju.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtmosxjyya.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtthztjkfn.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtldyknegi.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtkjnhitjp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtibqvuhhs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gteushellu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtddqswrom.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtvfojxyfw.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtwdnewxuw.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgskyura.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtfliwidhz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtxafivycy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gthfhmspub.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtucpsdwqb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwwylmvn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtmpyvemlg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gttedgrjxh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtblmzpabc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtwmclgakf.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gtxkfpufxr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtmkirmlbf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtdsqrzzur.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtelrboqna.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtkprijere.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtsqppeygb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gtnulaeagb.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtblqlplzl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtwayysmmm.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojxsjmdd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgvgnnwvz.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakanvqzl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwubolpd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtkzxvaegm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtaarzekyt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtppknrdxw.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbeguxbdq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtaumtayrw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gtjuledhmm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtznougmav.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtdpslcggm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxvsitlso.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyynqoftp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gtfogevqvg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtmgwyyczj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzwitaewz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqwbpvpps.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtgaysyyci.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtysbiclma.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtnujvaipx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdaerobx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtiipfjbes.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtheohbjun.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtdpdetsdc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtjbhunnni.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gtknsflurz.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtzmlrpndd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtyykovgef.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtkzlfuvfc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtfnehcdhk.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gtqpbgznaa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gteypelhuu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gtiawbzumv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtrzqiztua.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtglszbyco.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlnnuzulj.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtpspvseff.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvspmwivy.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtjonsqtmw.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtaqoyxvik.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtzjajjzpq.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtonhudtfw.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtzajesltl.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjonugju.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtqerwrmft.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtdcfcxffg.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtyvwopeeg.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtwxuvrkzb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtsftjxnbc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gtdpsjsdkv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gttyhttqgg.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtxvzfsmrw.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmxbtjkhd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtkfawqens.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtwewgmuif.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdzduvqcp.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtfyqfomfx.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtekfdpvua.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtgctmnxlj.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtsaudxshq.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtxcdprxxh.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gtsclexskz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gttzrzvcmn.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtzofkjbtb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gthjglxgwr.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtsxpzhwka.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtepbqeqtg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtpjmsfvbp.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtmryslnes.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gturrgzzip.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtbjcmxwtx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtkyflcska.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtactqcumj.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtnbybbaci.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtzbioht.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gttmvebxkb.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtdqmduoba.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtadwjssxv.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtlulklyta.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtggjcwjsb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtfwoqrjvk.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtdybfdmuf.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtiphdmgay.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqflbgea.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtsrcfdbyg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtvrwedenq.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtwyhhzkjl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtssawcfbo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtulygytdc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtlyqhedcx.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gttwyisfdh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtiimqrgoq.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gtwwfonxqv.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gtrynegssk.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtuyufliqh.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtgdeptoiv.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtwuwijxdl.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtlryrgbxn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtomsigrnz.html


<!-- 参考信息 -->