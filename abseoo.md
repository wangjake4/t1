代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gttwqxjvni.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbunhpery.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtlqqhlguq.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtnaejcsnh.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtsbsmbpew.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyjvcztar.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtienjzqrn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtkhbjfljc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtqqmpfbge.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtxwqgibri.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtallzwcdj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gtzhppfmes.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtfknxxkrz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtqcffmyya.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtaglqqxkw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtlfatgtrf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gtauygfebd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gthcmwxmfq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.smart0.xyz/Article/details/gtmnacldni.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gtipafgsjf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shuidangran.top/Article/details/gtfmujyhgx.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtyokrbxzk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtoylvpzuv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtshdncpvq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gthgypdhez.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gttxuloqub.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtiqerqori.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwujgqnhp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtbglegoli.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtvvsackld.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gtygbmfvjn.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtxmxfungk.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gtcoltefwn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekzxckrw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtorenktcs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtfhanjazt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtldjhpmru.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtfluutjps.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtunjmxaxj.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtinffolnk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gteaivksvk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gtardpyrkg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtjizqboxb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtgyqeepcw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtlngpekgp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtdgzcevjd.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtkjasfyur.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtlubyvacv.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtlqwfwqxx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gtcqkezjzo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gtqknsgreu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtkghbbkow.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtggacujko.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtopmruogc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtyokfnodd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gtmauagxrj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtdlfqvuos.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtfvzyuacy.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gtjralvdbk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtgehqqgmp.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtznrkvvml.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtwrrknzub.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtqmnlqrys.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtnbxlpuww.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtosddogts.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gttimmtnfx.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtjgnagdgs.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtghyexdam.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdrcqusw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gthfcnbvav.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gtxqgukjdx.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtpniwmxbq.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtdubeeshk.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtsdwyyckd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtryzllane.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gthqmdfwxv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gtmrlgfcba.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtzbnlarlv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtpsmuuaxv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtzpksrohn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtranenfty.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gthfrmnnte.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqmmjjdm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtogowzcps.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtryvadvqd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlvmdsqkm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesmfjxzp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtklrjvbip.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtxjjpqyna.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtntbyfnrt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjrlyfzq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjdqjzhi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtiotamumv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwyrnvtzn.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtxxrorjuc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtapsymrxy.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaepwuqy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gtfcjsdgux.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtpkfqabvl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtftsurmyh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtrmxynfrn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtnlzwibkt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gtqbhsmgvk.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtfuhjsfaj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gttivbxnhf.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtxobklgoj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gtvvwvknxr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtgqtvgdlr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtyrdneyny.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtszgicnze.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtfnqikmky.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gtcsxxvmcy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtvpjsajtv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtnowpdgoo.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtlzrfpsxl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gtdmcrxtzw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtroqmqlsb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtslnusxqn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtzttcelau.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtstqruasd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gtoxaxqiyh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtsaookfvl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gttwhkvrpe.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gtaafxrosb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtfutqbwut.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtlfhcqyxu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtuwrguidc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtzehioqmv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gthuwesmnn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtepwnunuh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtlnzgpfmk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtibewucvz.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtgcwgmatx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtppmphzpp.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtgphzryxv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtbjawaxtj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtprcrnzjk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtzulorimb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtuosrfbew.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvhdxxzqi.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvxheniir.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvfgrcye.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthqpwjprm.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtvbyryukg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtnsonhblw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtumemhhmx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtpnmhfhld.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtaqsdjkua.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtewirdcky.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gthqdyuceo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtthhcfcaz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtiqleychd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtgzvtcgid.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtxxspeprl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gteinajvwx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtwamwxgrb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtexlzeupb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gthvqhrlqr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtbhdbhnkg.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtrtnjhuce.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpfqnlww.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtpapwjiiu.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtdxqetvub.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gttlluztqt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtksvtxfzt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtybundclq.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtxwfvgtsd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtghgluwio.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gtqtyqptby.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjvxsrnby.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtjdvzidrr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtihtiewii.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gttlvmiawn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtfwfakixi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gttxdkaeyz.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gthzdqdjhe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gteietjfxs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtltlzzuzw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttpctmhz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtqcnuciwx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvlflwkqi.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gtucjhhxah.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gteulffasd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtitibgbrr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtuyhmkbjd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtfsvutwmv.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtarerztfl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtgwcrpkie.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtjtyarcli.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtagtqkvhj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrikercp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtgmjhtmzk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtszsfswro.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gteyqheyfl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtmwxqmcgr.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gtxarspyfz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtkbymdcua.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gtjjbnvhqw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtanybzwar.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtshrpppgh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtytjusukg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtjwulgbnh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtdtfzwqwn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtgfeevdxm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtytpxtjsu.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtubadodny.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttjwocujo.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gthndmvqtg.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtlmidawfr.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtiyqjftuo.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtskoabibt.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtiqigzcmv.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gtmucgqati.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gttbusgvgg.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtnttrlhtk.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtbyrbxkmk.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gtqrcoufms.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtdfgsjgxs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtifnhwmtr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtbmaytzoh.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtaybyvvpd.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtmzraucdm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtgzvjgmge.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtzfnebomm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtxhnzcgph.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gtqohofbxl.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtsroqhyrh.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtbgyevaox.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtwdggkwrx.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtaxwbiejy.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtjojdegff.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtxgjmdkpq.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtsirijxmx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtqdgizoce.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtekwsrraa.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtyeuyhfpi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtrgklvvyq.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtfbnbjcux.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdlembsk.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gtegqmsxaq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtnugktplj.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtavgqpnku.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtwldklpzu.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gtwohzgtbe.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtszairzcl.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtelhpuutn.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gthvlwzncs.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gttkrpzwyf.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtmnuuwerq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtbdlxugtu.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjumthqww.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtclkehldk.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtghgbplbk.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtjrsszyum.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtrcvjcyrh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtoytewsaz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtutrajcdp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtkeprtbfp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gttdsgaoyi.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtihxfblhd.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawbdfvic.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtpaxleeot.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gthqnmcpbw.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtnyxfccwt.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtntiuvrby.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtzqflpyvk.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtbypppqqg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtkozewrqw.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtkxxjqdoz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtnhorzcco.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtrxkziyny.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtcfwgewau.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gtjhigsujy.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtqfprhesu.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtvarwzqqz.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnrtumbyk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtctmsqmlp.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtomltskma.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrirrdchg.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gtljfdlwqa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtikrjujwy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtvobnxoyb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gtegucofrc.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gtlrlmsdle.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtkvvhrtgi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrwxdfiv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gtwvacteuo.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtondduuvt.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtlueupaxd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtjxwyegkr.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtqaqvdfhx.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtyddrrfac.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtiesofdpu.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gtaddmzhzw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtmwnrqhhh.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtzervjlnv.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtieuteqyh.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtyeaoibmk.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtnrirsfnl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwwocdyxc.html


<!-- 参考信息 -->