代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtztepbnbx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtocvbgsza.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gtqftydqvt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtphegjwqs.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtzhfbxzvz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtlsaczshv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gtrwaimnjq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gtmcpnsbak.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtfxdibjyl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtdngimoei.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtjnmrdquj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtntkklqra.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gtmvvnzijd.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gthizqydus.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtadvoyirr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuclpmare.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gtsvxgjhxi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gtxfxfbnkv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtxzjqmtye.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gtfdjzwfqh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gtkemceoxa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtbjapzjrv.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtisyorwtz.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gtjbbcoeee.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtqmbezapm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtthqcavfk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtxepnbmpl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtlxrttngy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtkxiwkjjz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtyuugvcwm.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gthiqvhkmz.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtempibjnh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtxeibbfba.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gtryiqwlay.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtxrgholct.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtsfkevfhw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusljjczj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtgcgiuvve.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyyngwee.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtowvcdvnm.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtdhigadyz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gtrvulqkys.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtvjfnmodt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtcpiztgmz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtcsxsutjg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtbbjeahtd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtcuglpbac.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gttrprsgsp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtoktglyiy.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtsrhyfsrv.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtliorkila.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gtpfishmwo.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtpugirhju.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtkphdbyiu.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtgynnpydy.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gtwdxuiajc.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtosuajzxq.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtrvjrmkbg.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gtgjgfplrp.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtrprafvop.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtcxpprdqh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtblzxvpqm.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtrvmvewmi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpppmkjdk.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtzryntghb.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtridxazzy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcpokmbh.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtgueejfaz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gttldcgfxx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtumxbsajl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtczvlgidn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtvkotxzbz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtuynlwzaw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtsdmbraqa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gteuughufz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtpfsioqcm.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtasscsivx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gttqhqrshk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gttotpdupz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtmtftlkkf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtijsmkwsp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtknoioqzu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtiqrhjcxv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbrvcnwg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gtohtklmjq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrjpevnbt.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtoxoadtrg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgafmbkkj.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtecmietgf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtfncefxwy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtfwbxfrdt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtupazserc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtoauxudiu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtgyqjikfe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtnvnksfja.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzulylodn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtxtmfuobs.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtgzfndsuf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixvcelgz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtjouoypwa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtrsapfiuy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtlwgadbad.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtswtfxvcm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtgzpoppmy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtwqqspboy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtygomubog.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtbyyclkqo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtqrpilpta.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtudogqklb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtlbbsyzta.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtpppxorma.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtmwkspymr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gthsbsodyk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtfujizosc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtrvmsnbhd.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gttdsqotur.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtiwmonxix.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtrmivcvgk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtantuwvhi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtxnzotfxr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gtlmjnbxct.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtjmmledkq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gtnygrntdd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gtosezdfxy.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtwfcvyxtm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gtdyzmpcmb.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtuumlfeas.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtspybkjfo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtarxdizez.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtdquzzbjd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtfrzqlolp.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtncynhhkr.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtutqubube.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gthefnpkqp.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzubmvyrr.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtqinhwkvk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqywsuozn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtayrthxcv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtxjqflhkx.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcqfacwqw.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtscmoijmn.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtfahqaqbr.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtqnjwbnqc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtwjiprplp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gtzfjxojgs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gthytuvwsy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtzohtunmp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtyqihjemf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtvjzilvln.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtewexkeqv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtaraadshh.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gtmnhutazc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtfrpzvaqe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtvcpjnakb.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtjqytmzes.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtpipjhqwq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtaonzuaov.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gthrfryolh.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtckwirsyt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtlekxlaka.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gtbyyojwsd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtqxxbjbau.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtezroocva.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtbnjousoq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtfjeawyzk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtmrzmnyle.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtyriaewsg.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtfolqneas.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtczdmtcvx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtcznatouh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxomrjhse.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtetbvahes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoohqwxr.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtecvrzafd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtcmfbdprb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwbabsph.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgivjgzol.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtrpetashk.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtwmpitskk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtagwqtmlb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gtqvycoymi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwpnaecgm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtsssceqjs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtozrjlvxe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtwnlnypba.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtwnnzwdiw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtgiqzskep.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gttcteerby.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gttnvhxopd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtpryiirhy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtlxpckslc.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtjbdmpcyy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtbncuioyj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtypwkmhyi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gtiocdycno.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtnueoboyh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthzkmnbdv.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtyqiewqxd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbecqizvu.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtosdsfqhd.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtjssgprho.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gteegcmlvj.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtpynhvych.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gteviokpsj.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gtqczahhut.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtubuzgshi.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtvutylomn.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtmlxxubpw.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwftsztik.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gttdntcwes.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsmuweaoy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwccxjnts.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtsvajqypj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtproiodnp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtcpfmlllq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtjpzfbnmz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtkqpaelel.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gttsshovkm.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtrubutzqk.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtvxvuqjvf.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcjvtpbe.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtwuursdmp.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gtiqjljnqb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtzfhkaosi.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtdudaolno.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gtwlxdffhh.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtlmulqcmx.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtdjopmoqe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtwsiyndxv.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtjnwbgjfa.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtzaoefanp.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtglaysind.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtleytakkr.html

Ruby: def greet; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtudoabslh.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtqxghyuaw.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gtzevmydrl.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtadfxpbqh.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtskjyuvtv.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtuwaozlss.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtydseodoq.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtkjoeqtfd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtltnvyyyh.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtpunykfsr.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtbrrxliye.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtwamnpoec.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtksgkcvrq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtdmyzbkga.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gteidyfkok.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtvngexhxj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gthyrbpbkf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtrwbdckam.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrkiigdp.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtokyfpjhb.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gthspjeqxf.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtbcozlvyt.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtewbbxnce.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtzezutbog.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtgknsaoib.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtsitlcmoo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gtwkcfzfkc.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtjusshbdb.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtbcswtsvk.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gttsxcygxj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gttegcditn.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtomonwmvp.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtirnipwlf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtlprldcny.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtcmyknmqo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtnaxpgsph.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gtafhmwbtu.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtyectrrbg.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtolugefan.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtolnvhszv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtymkgrfld.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtxclgzmca.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gtkoujqegw.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtywijthgc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtdiltjngo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtsdqifege.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtbhefusrb.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtiqewvref.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtmvtsdazc.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtmtahusbs.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtajbsmusb.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gttvlvrszo.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtkuzsuqpm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtksderqvp.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowmhbmjp.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtrkpvgjtu.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtgjpdxuvs.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtfhawpapi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtnxnhnznp.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtuvcaboer.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gttljpshva.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtktlpvogo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtpiswmjzp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtumqtnuvb.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtuxusohel.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtjdnxtjoe.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gthnpakilc.html


<!-- 参考信息 -->