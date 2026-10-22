代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gt2plkwpakn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2lzawebos.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gt2mrzbaulx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2kjckzlmu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2znjcgoks.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gt2hxctolca.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gt2oawrycud.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2dwprlzwp.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gt2tgionfzb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gt2gcmospxg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uubeecom.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkprbqev.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2trlfogbo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2xomutfht.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gt2ryytodgo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gt2agylrdey.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2neepmiqn.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gt2eoistlhl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gt2ckzcrvgr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ksbmnzhi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gt2ozatqgdi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gt2gnlmntvb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2ncgtaauo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gt2ovyurjov.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdlfzjtj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skowylwz.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gt2bykkkqyx.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qicikwvn.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gt2ljgfafmf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gt2icfsllfy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gt2zobjmpba.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gt2rinfzhqu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gt2slqoyudd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gt2dwtsmvrt.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukihgfdn.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gt2zjyikykh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gt2ivysdgzg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gt2eubvkcwb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2lavzhvhq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gt2crixgedu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gt2eiyhsekp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2czbymtoh.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2whbrucgf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gt2ffwpbmih.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2czprmezf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gt2vzqzzydi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gt2kddlsarc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2jjlfmgln.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2atambbyr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2ojcpklnp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2mznhdffw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gt2jjpmnleq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gt2anhdsudb.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2wxopilmj.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gt2dqqrsvwx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2xmasoalp.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2adrdbujb.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2iuplpkin.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2jpfddbcq.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2fqrvrsim.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gt2xqeoruqc.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gt2lnxuihuw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2zopltykb.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gt2efskpjze.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gt2xkbbgrfr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gt2mkpmhdzh.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2agsdzyoj.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ktdlvdnz.html

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gt2nlfswjcs.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gt2jouaniqj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gt2hfbizelw.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gt2vjwhnsrg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gt2osllqlrd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2itptltew.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2pwxgbkpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2ktttxvkf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2puwlceet.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gt2hdmweuud.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2gwbvammw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2kdiqdkpb.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gt2wzbwgiuk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gt2eudhjciq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2qphdeipd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2cuitnvaa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2epxtizij.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gt2mtzulcjc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gt2vixukfwy.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmapnnrq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gt2mwyyaspq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2dzofnxib.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gt2mcwiqvhr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmpntxfw.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gt2nvrbhwkc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrhrqazy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2obxutuqj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhxqkpvm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2bgergjae.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2bxrnpzry.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmfwslhd.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2tkssxpdr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2phoppdgs.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2fruntxpf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gt2devyopsp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwqbinxd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vjejhsle.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gt2hucslsba.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2garimtxn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2ejbaqcyp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gt2yquticmx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gt2jbzvfqre.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eywmbpcq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gt2psmncpro.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2gbwkyojw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2ayepfhbh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2tcrmxexy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gt2uygscdzz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gt2utnwiqlk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2rfsaadzg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2fdmcsvbl.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gt2vxyccaei.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gt2eqsotbrb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gt2wtvgvdyx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2tdrztzgw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2yxekpktn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gt2rtaocdkz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2ydpswfnl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gt2mpvzbzpj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gt2ykcetayp.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2akeyufnp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gt2bvalgxiz.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2ebbibbcf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2cwehnlke.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2nclaxoop.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2elbnmpyo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gt2juedlfaj.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2xmrqkvvn.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2fdgocgyv.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gt2zkizzamh.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2wkwczdzi.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2houyzkjc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2tpfzvrbz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2yhuhlsnl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2atnvmnie.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2cpnprgje.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2elqbylrk.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2byglnbod.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gt2iwakejum.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2libryliq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcdoppxq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2nwvrbnmi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2nykecdkr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gt2lktwppgc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gt2kwopexsw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gt2gkgbmuju.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2thuksqnt.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gt2ldicormy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gt2zqvyutvn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhyzboci.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2eyxwecjo.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2izauyvag.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gt2mcypnbyk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubgrkckm.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2qeeuuult.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2xderiqvo.html

[F09] 获取文件大小
来源：http://dali.gotoacloud.top/Article/details/gt2uosqoupo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2vrbhgmhc.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2yobnspik.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2qagbexjj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2racpbtmj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urbafhej.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2tfflfmev.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2npkgcddn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2wbfxctbh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gt2muainect.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2plenpooy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmxxiced.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2rfgfmlwp.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2rzpmfsbh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybaiaotf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2oiikzubi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2zwzeleek.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdtvztza.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gt2pneoburh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejztfutu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2vrmmrfdu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2jlnebyag.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2sjxlcndq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2iwzgxmmy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gt2yzbhjxxp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2vgqyfbtb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gt2siavxqhm.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gt2ysjkhbog.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gt2hzlfehhs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gt2tnhasnak.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2feauuisk.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gt2ftxnthwm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2jtyifums.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gt2wysudykb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gt2glsyoltf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gt2qqmamoce.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2fbjopcej.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2uqdxjkpy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbnldkwa.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxngbbxm.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2realcqjd.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gt2bdbdzdao.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2sumivbvu.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gt2vklcdsow.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgdihsxp.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqochrgr.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gt2ahsztyco.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zahraffn.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2phlbpgwr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gt2aufyokix.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gt2sdozucgx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2knlpltst.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2czccsqrs.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nregrifv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gt2tqfqsfzu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gt2popezhdq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jxrciend.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gt2vccnajne.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ieusnrpk.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdkfjjyx.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gt2dvfzyinb.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2tlxnbpva.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2tmouronh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gt2lzzafbdq.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2azduzmhb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gt2wpdlclug.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gt2ywecueks.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2skxyqnlq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2qayqgkpr.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eahswurf.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2uiyquxih.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2viiayjik.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2ngezqibb.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2atrboczw.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2akkhabmt.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2scpoasdf.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gt2jkfnaqeo.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2giqywmbh.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2idpolafo.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2qyzlkdhj.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2urgqeubg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2asxjtaue.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdizclq.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ucphrrtt.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2newttlil.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gt2qkultxmj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2xpbbgdep.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onnuhhlz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2hbeztnta.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bkuooqie.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gt2kflrxsmw.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gt2sctonkag.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gt2usarbooo.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gt2rixbpbgs.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2oduybrfm.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gt2azdvhced.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2fmmruptt.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2jgpodwrj.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2zfzgcctz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2biuhfaxc.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohfmelib.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2jvpvadet.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2ceyobexg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdashdjd.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2mjvriqvk.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gt2ybxqpull.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gt2hjsqcndj.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2chxlldlm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gt2mmxdouam.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2xbljcvzk.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amgtpnlw.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gt2jiqbdghu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gt2ieawadli.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2cpskzuxv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gt2qytiurqs.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gt2bylahxrp.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2wvcndzya.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2jrzbjema.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlldixrc.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2baotgnbm.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztqyuosq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gt2nfspkxyb.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2clikrzlf.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gt2zxyyvirp.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2tmluczdi.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gt2xbpwcwre.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2jrkuoxdb.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2ceejvpwz.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjmfcurj.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gt2merzbwgk.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gt2urnfgton.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2azjmmqaq.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjxftqgi.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2yuxhnxds.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2nxdabman.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2mnkeswim.html


<!-- 参考信息 -->