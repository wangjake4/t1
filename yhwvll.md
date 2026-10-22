代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2ytytplkm.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2rpcbqwch.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmeytet.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2qbvpndqf.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2jekvcsoc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2gllzivbd.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztexowgf.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2svizowgk.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gt2viartiav.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2hwrymfhr.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2hhjmjbfs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gt2smzvqgjr.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gt2vkeswjim.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2xdbvngsy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gt2ggxoxium.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gt2hdpwknlv.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gt2uugqpted.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pltiavba.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2jlnelgfr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2itgiilpg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2amwngwnd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gt2kbomtymb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gt2fztanffy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2bgmjlwkc.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gt2ovgoybwx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydpekgxj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gt2kmnznsdd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2kwuiqpnz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2jgcdhxvp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2dfonabbt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmhjcytg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gt2ebjicpji.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2felibiba.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gt2bzpsvkop.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gt2kptccaqt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gt2egbjslfc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibyjkvmh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gt2sssyzaqp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2rjmjsinj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gt2iqdvqwtm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gt2mgqqmojc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gt2karsakty.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyanvzfp.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2juzsqmze.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gt2khaelxlh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gt2qlakzogd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gt2ftzayxme.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gt2yfdgvhtv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gotoacloud.top/Article/details/gt2vmmzzvak.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2qjytothv.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gt2melmakwi.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gt2yaofedqd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2klrzbyri.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kavaiecy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njqlusdr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbbaldar.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gt2iexfzylo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmqeargv.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2xqmfgowi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gt2aaiwecje.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2uvbbjnkr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gt2icmhrnex.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gt2tdasjepc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2yzipwxtm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2fgrwsuku.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2smykivwg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2hcajireq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2wlcpvdtn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gt2mkqivrhs.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izmwvdyu.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gt2jiulirva.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2inefcqfj.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2pwivloqf.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2gjjlktid.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gt2hnksdcjc.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gt2kubkizvq.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gt2alsfmgdh.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gt2nxwgkrjb.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gt2xuakxjhy.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2eagursik.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gt2tdgmcyfi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bprlwqsm.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gt2bssliquh.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ibudhlfo.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gt2cguqteqx.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gt2qgrjkxjd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ahqpfqtl.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gt2aqphihnx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gt2alaobthf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yntxmetk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2saxjjyqz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2iqxilxpn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2zgedkrin.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2veuclspa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2pswqjich.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2kcudgsec.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gt2xidjbzgn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gt2rwyskwyd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2awodljqf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2qehccrof.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2vjnhioxo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwkpbuii.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gt2ibmztlly.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2swwxniop.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2tmpldodc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2dxxtqhhr.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gt2voejgghg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2nznpleii.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gt2zviuwqab.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gt2yfkawkrv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2vpsclwes.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gt2pelrkcvy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdlhkjuy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2yiryznnr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gt2rxpogqih.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2trznyhwo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2hanrsjbq.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gt2xclyialu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gt2myxrayms.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gt2lbcvjzjq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2cwheoard.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydfpxovr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gt2cdjdnvrc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gt2ddgwyays.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gt2aflixfgu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gt2mekbptwb.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gt2hijgcqfk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gt2qpobruei.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2ktezijkt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2bmrnzqaz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2mdcdxtsw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2tpluwjpa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2xqzuahrl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gt2ftqfjgve.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2xcbxivga.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdtgvwdc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2gkdmhqeb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gt2vxkkywky.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2sfmcyliz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gt2qltzkwxh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gt2robfbwvb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2iphxbdid.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gt2lebprpgw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gt2ntmvejzn.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gt2veuuomto.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gt2vozbwzsf.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2rnqiaxcx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dbfqdlqk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2aezryjic.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2mreqskis.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gt2spswfxud.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2qbasldax.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2wnigtpvy.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbywimhp.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2cizryoje.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2eblbstdt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2jpxanysp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2vnwupotc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2fcfxxupd.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsldqudf.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2jbxaaste.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2iuyvmwep.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gt2ughspbto.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gt2ahkokehv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcmmvydl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2qssoapqt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2dlpcoxjf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gt2xuvjtbfm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gt2tbftdcho.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gt2wbsufvmn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gt2kgmcfnrg.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gt2wiovzgrv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gt2dltyjnjf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gt2ofcecyyv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2hjxyemjf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnayzrbq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2blqurwgd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2pcembepn.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2egtzgplk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gt2gxsoqzvv.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gt2dxkcsjun.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2xoehsejf.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2zdsqfuoe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2lnoyntes.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2pxiooeny.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2ziieqzmq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2cbirphav.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2goobnqwq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gt2smyerylz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfdwkbcq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2zcouxitq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2eknvuslc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2kqztnivj.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2pepkmqqg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gt2hzcfelqu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qegkkfje.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2xlnpihbg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ctglfboq.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gt2jiksrwvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2hhlvnstw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gt2shliecmm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2puhvpopb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2lituxsmj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2dwooznib.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gt2bgxqnuyj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2azjkbnzv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gt2yzzjlvxo.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gt2ruuauooc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2lvexorkr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsbgmezo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2mscogmlj.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2nxxqntob.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gt2sactxciq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gt2jyqiqukv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gt2wrrulfsx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gt2twcwlkjv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2uyhvpnzb.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gt2ufyorycj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tqvfxomb.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gt2vsfnkgma.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2alwxowrr.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2saqpdrrb.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2hppkorvk.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gt2gryijwqq.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gt2wyusdogg.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2yzuhifke.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsdtajtd.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hexlvrbr.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2yoaledzx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gt2wrhgkbny.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gt2pikchovv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gt2egcxgfna.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gt2dfainqst.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzfknvok.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbndoujx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrxxjfjs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2xljglkyf.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gt2jybkejuh.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2ozojavai.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2wndsiqtm.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2hljabajl.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2gpwjioif.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2kuamurfr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gt2nhuaazic.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgprogfu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2zytmaliv.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2jnbdzzqi.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2kgqgybey.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ireshhui.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2doojjgvc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hktvnawg.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvsnkngj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2roewdbvd.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2lvitfqro.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2jhzfjduq.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2igrittma.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gt2dckoezsf.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2pkfiouno.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2nyduideu.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2vwfcxpcd.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vltvdaqi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gt2nozbwgrs.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csugsuqq.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2mkrxfobo.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2mauxwtjk.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oaiavrsm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2iulnarwk.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egavvhxn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxseujd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2wcwxgcah.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vulhmoxi.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gt2elppsbwk.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gt2yipkgxsy.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gt2hatdjisg.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gt2jbgqdlll.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gt2ljxphiiq.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2woihhhze.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2cbflifhg.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2ythbczmy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2iktmajeh.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gt2gjlhqqkx.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2jlrrbcfk.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2irjsnlwq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2xrrkcxqt.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gt2ycunbtll.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2mevvnxnw.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2ddzjonyi.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2iztlisnh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqnoevvh.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2cqgsnhxa.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2govkwldn.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gt2aiudlzmg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gt2actbsyvb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2azbmoyzh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gt2aidrahlr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itahrebg.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2qesmcdkm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gt2bfenbgxs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gt2efkzkfeh.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2iafwmyak.html


<!-- 参考信息 -->