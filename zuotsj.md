代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtwglvyqcd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtdgcsuwzb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtygkuzesj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtwbfstbbn.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gttuhaoshu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtkvstgtjv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtobolckjl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtrqyfswyb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gttodldubr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gtyeqemvfr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtoykwares.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtrtbpcknc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtsalmxswc.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtgldbwjps.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtnzscicqu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gthbbxxvfp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtrazaamvr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtedpvkpyg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gttodmsjus.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gttzhvqqqu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gtyrhxaypx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtejupcbxn.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtyhzkvmhp.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtpqxeqalr.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtlgrorgrc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtgooqdvhs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtlkiweycs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtjreddoqs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtzftbewea.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtbdswdnzr.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxtqxlim.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtgzmivgus.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gtosxjrbss.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtoswppfvq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtxhaqborh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtmltbltpr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazrbahbu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hywenlv.cn/Article/details/gtcbmiddqq.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gtwevsbqso.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtecyeacvv.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtgtuieqaq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtorijvfqo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gtvivpzwpv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtbtrqgunm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtwaejqknm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtzeslgkeo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtaducjpkh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtotjxehkz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtzpmhyhwl.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtvpfugkot.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtsljkyouh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gtpejuteqh.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtaxcdayem.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtnqsrcnhx.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtiabrqgfv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtldmsduzg.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtfnaeccws.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtaudjwpwl.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtzadgougz.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtsirxabak.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gtnivjksfs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gtecespqqw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtnkdnhrhz.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebdjucow.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtpgoeiznm.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtuuppahlj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtlbgrbhtv.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtjzvajcbk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtfegoamlz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtajiwyhis.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrrxeufz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtdnpdzixs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtgfwqzvwm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gttaeuyrls.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtcysegwok.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtklyvefof.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtmyekgiax.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtzkaxoctg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtzixdxhlg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtmpmoclob.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtegdsauky.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtkxcgwbpo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtbnqgyupa.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtcuynolgf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtzisybrsi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlgmoxuiw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gtmrvuashf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtokdrcnhv.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtvrpoygja.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtnlsuiqbd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinvtmzqt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtxaeaeauj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtgvdmiuyl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtvqatmdar.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gtylymkleo.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gthgfqivvp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtjolrevqg.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtqduiydjz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtzobbebtc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteqvwzvbg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtqjjlvgxb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtqubspmus.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtfxzznnaz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtgjbbpwuf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gtjzvuexdu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gtlotzavqn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtstipedmb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtxgeseetj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtytaxnfnp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtwlzltxlf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtnovrlnbb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtqooqgtdg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwabizqw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtbqbwubdl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtqchwddpo.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gthoryepxy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtzqrwsobz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gtuvdvyqxc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtbkoivtbx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtzhmavekj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtsfkhrjnk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtqgscbjiy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtjgvkhjyb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtevxndkoo.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtcxkgrfkj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtpvdtcxis.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtfidravcc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtautqztbo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxwfcysew.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtbvqobplv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gttcocupei.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtswuxkejp.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtqmdfvuez.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtodtbupjg.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmxioeuqh.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabxllqnj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryfniusp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gthpaoypnp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtouvroqyx.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtyvlmrmaq.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqapcbdga.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtxhtuxvqu.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtwgrcqkqv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtwpzxwhfd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtcqdwaxml.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtebwcdghr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtzrlkebol.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtyoqbphjc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtdwjtanoy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtvzxakzvl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtxrbtpflw.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtfwzaaovk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtmmfewnbn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtcntcdfxf.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtmrzdldej.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtpbvgucll.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtfjlkpbdf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gtlallcxkx.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtoxzzmymq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvrlhjiz.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrxfmnnr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtnpezqlzw.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqqtbcfzq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtnfahggzn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtebicrsdo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtpubisbix.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtigsbvmky.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtxqckhchn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtsgafdgyt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtqzmnaftq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtlzjiuvpo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtvyzezpjo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnjstbqoh.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpzqwcpdv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtjqeairwz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtajhlfgml.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthfnurnrt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtipvnibez.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsenuzwu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gttbcszeta.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtbozagcow.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxbtwosg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtevacegyk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtgikyjstk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtegtoajdv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgmuhgjd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtazgenzog.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtqcyiwqml.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gtvvyzujxl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtblnixnnr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gthhjjmsvt.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtrxunybtc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtdctcbqtt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtswhnbvfs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gtmjmlbisk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtodluogds.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpmulfrcy.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gtotraccnl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzkxkcvft.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gtwwdtswdr.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfwnivbs.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtzmvtkzql.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtycgrnmns.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtwobijlxg.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtknxoeopg.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtweyeaaxp.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gtlgsnwjua.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrriuaxm.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtxfvgfvek.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtewjpnbro.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtgrcrdxjk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtxykxswbu.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtislqfrbl.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtuhvkhraa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtpufnorkb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtwwmgxkxp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyftroygb.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gthndyaegd.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gtflajapfd.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtgnekjlfs.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtiurdwkau.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtyqbreqdw.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlixogler.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gtaonhzebs.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjudlgajh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gthpikogxf.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gtskzbztcu.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtzztieslx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gthhbxhhzp.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsoobtsat.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtfrgrmcyi.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtmywzrtvc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gttqbgtnwk.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gteaiznjcg.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtlyozjlte.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtjjxhgmfq.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtmwugomwx.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtzyamkeoh.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljnwbtnu.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtuhpbitlj.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtatjatzmg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtczxqypno.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtfgllfdzt.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtkuecejuj.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtdcsxxabi.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gtsaabbxai.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtdrsmtxhv.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtkvdtvgcz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtlvigwfoh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtumpkpnwe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gttggavygt.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhhvnpcy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gttgzffbfs.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtcqgogcds.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtylicnsgw.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkgavazd.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtjpxvofnk.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtlexfurzb.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtmhechwxa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtdowzjmmf.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtrzhtaaoe.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtaixmjszf.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtizduofvp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecinxwae.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtilwawvup.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gtgtkkdvmg.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgxzvqfvf.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtbtrntmmz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gtityihuju.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtgwcfysvm.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtdzpngehh.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtofgvmuma.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtbwlyikql.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtydsuezkn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtytcgvsrm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtpefjbopq.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtftmwamre.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtkjqvuamd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtmycheuzd.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtelmwsdvi.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gttxraxaig.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtryhvydff.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtaoqvmxaw.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtofzqpqvy.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtihpftlgm.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtrnmtsitx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtdeystwou.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtubrhvgoe.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtewpzaixh.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtyjjkjupp.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtiahwwmqi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtsibtvnks.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtaykzcsob.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdunyxfid.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtowudhumx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gthfcnxuop.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbcbrwdb.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtsorofoqw.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtodmbdrrc.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtnrdtugxp.html


<!-- 参考信息 -->