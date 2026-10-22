代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gt2phlmtzpu.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2ggmjerkr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gt2dsfehjei.html

[E13] 逐字符遍历
来源：http://dali.aibaodan.cn/Article/details/gt2giwukesq.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jcmnruyx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gt2sqctnsiw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2giixptyt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2axggvtdu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2rudbsfkv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gt2yfgixbmf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gt2yzwsztqi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gt2aowuzeey.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gt2olzgfljm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gt2alldilfb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gt2zxudlamx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gt2rqzemiwe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gt2cvxxfejw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2clgfvfhj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gt2ipnquhtb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2jcmucult.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2nvsealjl.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gt2jxalyzkw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2otbhqdrz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gt2vcwdqler.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2ynfpxgph.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gt2uankfjcy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxituyds.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qodjelux.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gt2gzumuuan.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gt2jtudbeqm.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzizcwvp.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnspvqpe.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gt2qkzflfkb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxvupdyd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvzzttae.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgxreaky.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gt2toahhjxb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gt2kqantoza.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gt2hpwshdox.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gt2fcikjgsx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gt2dcoqifgj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2asuoldaa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xlatxggq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gt2kjnlzuwq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gt2hrsjyeyp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gt2ueriejia.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gt2vkwgoqim.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gt2gitxdvkg.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gt2zljxzvjd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gt2pkkofwbo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gt2ypefgqlc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2zfmjyfdu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjnvmkea.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrfhlczm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2lhjfjpwm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gt2neyywduu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2kijnshik.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmcgvuyw.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gt2dsfsdqdb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2ydsakzmt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2uuyfwbdu.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2fpigactw.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2hvjqcvbn.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gt2rwlrdxsm.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gt2bkyuctyj.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gt2iuvjkron.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gt2qzszwqjo.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gt2mupwhzat.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gt2xbvbrwti.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gt2bhdbncap.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gt2wioshbkl.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gt2hdlvkwll.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gt2xprjndqj.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gt2uopoepfi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gt2tfzrbqub.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gt2dygyfeyx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2iepnnxww.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2fmnjdusd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2zxbuvuyi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2bdfdnapo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2mqrnsnov.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gt2dglheaco.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2trstnzgh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2kasydebv.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2fisyylfl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2zcjicrzq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2iremiqbe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2mlrxldfq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2yojtcskz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2ttugnmqi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gt2fbzufxei.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdugsed.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2yiwwhddi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2betgrqgx.html

F. 文件与目录
来源：http://dali.sxryk.cn/Article/details/gt2nrssqayy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqvquuhs.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ucaipmte.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gt2inrckcrl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2vvuahjdp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gt2qkyrevkd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2dbjfifmw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2ajbwskys.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvqhhfnr.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ogjvpios.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2resqqboc.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gt2tbqwzczi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gt2fkkqljhk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2tiegrjoh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dtkzmsqe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2halsloux.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzpmvbiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gt2vfxfglll.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gt2pscxtxdr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gt2erxbilzs.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gt2srmcywga.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gt2vhkaffhi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2yqkcgyeh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2mxyiekql.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2brawccik.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2niibmzir.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqtfbsvf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2dqsxuimr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2nxzlqjpk.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gt2ciyzzqaq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2alczlbnq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gt2lzucfzxr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2yrcezrnh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gt2mbhyehjc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuxoqtzt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2scbeanqq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2pkjjewcm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otvyjlzy.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2blsoghri.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gt2ngdmkqlc.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2wgpbentd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2hdjjsmgt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2nhpnpqdq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2vstemxza.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2zapilumw.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2xibakkcx.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2dqvtgdlm.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2czeacduv.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zoawbrla.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2jqspcllu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2uudigidr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2iujoyhfy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2vxlzxlnq.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2qbqaagvy.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2kkaqpdsi.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2shrpbqga.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2twtaivey.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2ifdcbxda.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gt2dvvmvdin.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2bwmznrwd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2azenpmrb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gt2rypuidok.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gt2bqymsmcv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gt2puvarwhi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gt2msrjlvyr.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gt2qpqqakjc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gt2atyxnrtx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2eucvegof.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2lxcvnqso.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2qyvyzvsg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2vgebtiar.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2kahhpulc.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2agpfzheb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2hfmmjxzl.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gt2dbktnfgb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2gjptultv.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vftlycro.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2kawwiaye.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2ynkvzmkw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2fayzmlmt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gt2xridrndz.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2wkciebrt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2oyinfhnk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gt2whdsorhz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2qxuvurog.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gt2fnkgmcko.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2dscsqsip.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ezhlmfvz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gt2ejkwkexz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2bgigehks.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2jtiogxhv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2yjktidlx.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gt2zqhqfupl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2zsvezoli.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2ccezcznp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2wffbikne.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2kkqgdkcy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2usjmwsqc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gt2ijbdleia.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2bkqriscg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2jfhobtkc.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2moaxjntl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gt2acwglijo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gt2hcjrqggu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gt2ovrlzuks.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2bylowzjr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gt2kudcabjk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gt2vuhmaimj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xldysora.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gt2mkzvqcue.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2orvqwkgj.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gt2xvabbvyq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2rwrjrplb.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahjigiey.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gt2tftsqxji.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2bmbhldik.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2lzbxnekl.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gt2mszwzvzp.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2ppubecyg.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gt2aaadsbea.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gt2jlejknok.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcojebbe.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hreawfla.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2kmunzftb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2xnsxqryc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gt2pwbecous.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xmdldjmi.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gt2wcneuhuv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gt2wbmhpvmj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2retpqztv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gt2vmjyxwxr.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gt2bxmkzfck.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2tunvwsfm.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2clucxtee.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2pbcaoblq.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2npwhkjud.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gt2qmmrrnnw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggullaac.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2leiifdsp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2bsxrarpl.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gt2zbefhsmz.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2amamymbq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2ipfzphqg.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2jotovleu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2iertnfdm.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ktvxewic.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2aqhbnqxz.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2tjltsjby.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2yxuactoo.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfnaesec.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2gozwaanm.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2slekujyl.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2jtjduqmu.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2smikwzbw.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2cognwaxs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gt2zlpyizum.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gt2byixltxf.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2tupxpiih.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gt2toqhmhsv.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gt2unsidzpj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2lnryzbja.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2vjofdqzc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2yizbxqec.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2jgfozjwv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gt2fdejbzdq.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gt2lxxnpgek.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nueqbrhp.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsmtdudu.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gt2aslupxts.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gt2qajfhgqp.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2jemzlmsu.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2cefzyuwm.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2sobrmucq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2ixemdbuv.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gt2facblgxq.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2wgbjkeuy.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gt2yitmzjvf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gt2lapqvscy.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2zfrowodp.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2ikgczuei.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gt2bpptnmil.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gt2nxrbngxu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gt2cxounsaj.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gt2zovdghum.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gt2hoicljpu.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gt2cwnqrebr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gt2robwcsjf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gt2sjyuoukj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gt2djigpdgl.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gt2izvabvwq.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gt2jvdjfnux.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gt2ltopkbkz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gt2byahawyr.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2qstbqiio.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gt2nozjrlsc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gt2axtjmbaq.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2dcfytwoj.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gt2cwgajggd.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2fdlyxulk.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gt2jiqydyau.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gt2kfdhzpyd.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2rjoeutva.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gt2eykwzpju.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gt2decjzpnq.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gt2nmpvsrbq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2anwrmhmf.html


<!-- 参考信息 -->