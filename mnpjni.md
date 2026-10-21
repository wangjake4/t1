代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gthrziqsbo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswawpbiy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtxvbpksth.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtqhdkdqnz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gthyirxoxy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gtbxlhqrof.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gttsxlvwgj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtkzxbmlng.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtguoexrlx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtppnbdibw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtaormnfkd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtptrzqsaa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtjdqcvttt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtsarmsrxk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylboaxkt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gtxrssrtyo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtgiixqjnd.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtlbpkrtfl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtcmqqcutk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtqweqydqs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtwcglblne.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtvqanoonb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gtnouiulxw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gtuhjenmar.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtttnxcwhs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtetvoqssq.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjztmwpwd.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtitrnurrh.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddmgjzjw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gthnwdpmov.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtzqqtefxz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtuvnwttjl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtvftlttca.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtxbcbgnvb.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtrtfcwggz.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtdifwipbw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtenxwgrpn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaynhphi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtlytsclhg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtzsilyhxh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtqpmcdplq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtruyjkfev.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gtepgxuqlz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtkiilec.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gtnbvzsgqo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtmbcmtevd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtvplsupdb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtezagyxyg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceceotnk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtfozxnhbl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gteaofnxxo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtvlufmmpy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gtcungnckz.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtoghwqmny.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtzkgppwuf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtwwnzhjay.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gteauqeezz.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtjidcztzo.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gtwgxtzegg.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtznxeyahl.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtzlouewic.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gtqhwcbynz.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtznexvctb.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gtyxihqkxj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtbuvvooic.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtcxewuxmq.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gtgotpuawt.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtbxsctvpo.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtwmsckvsk.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtucaqswhu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gtkvrtjbvx.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gtaezojouz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtnyxjyoew.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gthmrjcisv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtigweoapf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtpoyiksyc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtotuqbwpn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtetjjxwtr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtqhapcizn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtrcoaxuyr.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtxzztttxx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gtilpgwtzs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtbhpcfpks.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtdsqfwkjs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gthfrqsngl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtoldldjll.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspqagjdy.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtrnwmrwbg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gtzgghawsk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgoyzqzwo.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtuxnihgsg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcirbkvjo.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuunzjae.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtrysljvzg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtrzfjuvfv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtgjviuylc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtqzhfxnea.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtwgjbzxml.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtyxbxequk.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gttkclmlsc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtnqzhdobz.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gtpxtvmlbs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtoerfnjbf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtvaebzkpx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtgpdrtbit.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtmqpqonko.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtycmvnzec.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtnykgvriq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gtxlfntwfi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gthjkqsqng.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtgahhtmvr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtecfndnfg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtnputselg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtrqczoxcu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtononkuaq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gtwwompljy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gteirmvoyq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gtwjoaezem.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtovdfuafx.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtiarpyqfv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsxbpynx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtbubbvanc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtqqrouehv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtlqvienkf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtyeserzxl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtvnijjlyu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gtbjwbpwov.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtsxyflmyx.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtmuanprph.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gtdxqkjatq.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbvlbqqs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtqawvciui.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtkqxhyxsu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtdznzuolm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gtmnsrubbw.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcnemgvip.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbeqbxln.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gtqgqltjln.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqelqwzzy.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtrttrljlb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtlxvpjvab.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlxywgbcp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtlcofyucg.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgrhxfztb.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtpjfsooop.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtiwkervpo.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtjnjcwhls.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gttipxegmr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtkclctazs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtxeaiugoe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gttkbbgecf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtuyobmpkj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtcqmprtcl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gtedmkrqnr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gtmsyekxio.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtjsrxrhne.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ivvv.top/Article/details/gtwviuykom.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtqdsdrsag.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gthpnpopup.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtmqsvjaqf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtmumrcwim.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtivserlgs.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gthwwwyktp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtbiiiohwo.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtcsexblkp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtyizwmdgm.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtkcbhwvwv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtgjiqhout.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtbulujkzh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtmrxuygnw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtdsfnhgff.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtpcbokshq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtynbvslpo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtbzzjnjzt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbrmnibbd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfrkfjrp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtokrspyoo.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfgodcjw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtacnuyvpl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtblwrgxly.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtwhyglteq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtqzdtdxch.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtvtwaqoht.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvngmbyme.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtrgtlmwhl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtteqmioxa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtectniwrj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gtbdkzdsjc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtzvnxfnya.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtvbakdbue.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gthypndqmy.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gtqoqdjcly.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtcipsjoty.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtndwjewmx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtkezvkwxs.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtpxdkqfpj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjoysrmq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtmntfcexj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gtagbzlirl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtxnghvlwy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmdxeciee.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdsjqrla.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtsymjmkfb.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxjzslxg.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtniqtbblv.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtknvpfgmq.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtzgljivsx.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtgcwobapa.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtxeyuxzzh.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtitqsnrby.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtulnvuxgc.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtqasemejt.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gtbyqfqtbt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtrkzuxjmo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbqdpkdfv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtpretigfb.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gtiqyuyvbc.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtwlasaxco.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtjecislgk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtsdtqyfjy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdktskrcl.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtkgaqvdmo.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gthwjyecsa.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtfggrjlxp.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtmbqpmeib.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtqyzjtlta.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtmjxsgles.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtffqsgxaa.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtdmmpojuq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtntmwmdru.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gtjaxyqywc.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gtqakxqqof.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtdqplpkhe.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtxkuffygx.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtstilblxw.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtadtceiot.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtcfoyjlcv.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtcddmgnin.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtwtzwegva.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtogtqfsfc.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtuzzgsqrl.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyhgkuhob.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtoggszjvi.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtpzkmpusl.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtolewgkas.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtjapthmom.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gtbxdgvgxd.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gteqqucoib.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtqlmocxqi.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtzdhnerzn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtvbsfflhm.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtbpnpoyyc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtdlszvwrg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtsyglonpt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtaqnjuimw.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtdpoirilx.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gthgmktbru.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtvlreficx.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtkgwgfkcw.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtaosvaiee.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtdkiklkkl.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmygmrsj.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtismukbur.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtfeovlyzw.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtremthyqj.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtzqxsfhdh.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtbyckculm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtedihmcoq.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtfepiyivi.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtskjtmoxw.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtkzqysobs.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjmovljmu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtcaegqsbb.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtynkzzhvx.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtdzyfukmm.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtyfjcpmgb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtdwuufobe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtpuscvmib.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtjrpthrtf.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtqtbuuloa.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtsmxnisjz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtbrzlaqyu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtwfscpnvv.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtqckaddwp.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtczpoxeiq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtzdmtpjcz.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtzmfsceel.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtxwixaqpv.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtshdldavv.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtalzpkriy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtkfpiolah.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtbckbpxcn.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtptrdpugg.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gthonjrzol.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtqdigfkbk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwpsyupa.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtzuxpwxcv.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtqzpbtqko.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzijimqlp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtwudingxq.html


<!-- 参考信息 -->