代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gt2gvogggii.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2ngphbapp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2nhtlpbxc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2utrxjpce.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2jbyknqhp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gt2pnedxiwb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gt2kkpwifjq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2ziicpdsg.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gt2umuenntd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gt2wekucfdl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gt2fnyiwmch.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfycrgfp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gt2lmltcjyl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2dunkuemd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gt2ruhxntca.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gt2hrxwdcka.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2nacounrl.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gt2amephpxb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gt2zyryontv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gt2aolakckx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gt2ajjhpagd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gt2fzmowvjm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2zwoihikt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2cvixeilf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gt2wnmlsucg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gt2ljzegyxn.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2tswqgvkx.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gt2xqncpbxg.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gt2kgbmftkr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2flmqdjzz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2pnxgmyps.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2phxeodai.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gt2mqedyaat.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gt2mpqohoxe.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gt2wwmfdskz.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gt2nkjuoiqm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gt2ocrwnckz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gt2lemuytnl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2siasipzw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gt2xmxmflja.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ahiesxct.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2eemxdntn.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gt2vzciudfp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gt2nfhzkymb.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gt2lmixfxxw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gt2kelrghzd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gt2znjepjgp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2cmoezzda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2uzrvnvqo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2ydwvzmrd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2zvteagia.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gt2lkitzwgi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gt2asjmuucc.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gt2ssiuzblv.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gt2bsrhlotr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2krtmimbx.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2qqayxlga.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2fxellwfe.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gt2ycompand.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2ylpmpgos.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbonokrb.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqbffufg.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gt2jcpyxybc.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gt2nxavtdqz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gt2vmkoydkz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gt2gxmhkebp.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egcxpkgf.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2fbjhhriu.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gt2ntvhwkab.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gt2qrruuqtl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2tkfmwzfv.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gt2scjapnep.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrovrnpt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2hkgxpsrn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2udhfdbyc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2awlfjjaa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2qjmijhjy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gt2axtbbtgz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2iwndrwtg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2eyxdfork.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gt2immmdkdc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gt2crbujlwu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpgthnre.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2afutullw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2iuhbgcop.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gt2krfzbukj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gt2uldhfldr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2neyrtqzq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2dsdjcbfh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2smaxhnst.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gt2bshgeoqf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykwhtskg.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2stlbuesm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gt2jwaywrdn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2ebcbqhdz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gt2atycvsti.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2rkqnfkhy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2qxlaqcyd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gt2mhodjaah.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2nmpryjem.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2strcpfos.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gt2krxgnhxj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gt2nzjjykth.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2aynbmubf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skskcznp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2qrjbdckk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2mdwqbmbx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gt2bxihsqdc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gt2jbxjaryn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gt2nlcidznb.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gt2avqvegan.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gt2feefbiyp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2zwsmtoky.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2rqauywis.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2oilfxvyp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gt2yappdzri.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpklszsj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2faoqewfh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2rxdcwaig.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gt2sdcbqcau.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2goencwmd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gt2knugxkrh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2hwllkagg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgchvjbz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gt2uuesunqr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltxzfubg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gt2cgwidcdh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gt2ycmmrwco.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2bmpfcyrm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gt2ausfyekk.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdfgxdnq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2eyaskari.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2bipjsbfc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2nwgbdkys.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpkoynkh.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2wtljujqi.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2bldrffgf.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gt2yycojksw.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2suhquhjb.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2dhrsvhgi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2klbbdfvg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2gewfgrdu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2gfvwhznm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2bncfhshv.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2shajydni.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2yzsqwvic.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2aadpueyd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gt2blemavto.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gt2ipxkkqsb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2tycpvsfw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2myxorhzg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gt2zgabapps.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rohoqcyf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gt2fkczzxsx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gt2mlbvmigo.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gt2fvnibcey.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2rzouzblr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gt2nqcpogqs.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2vrjyootu.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2suywqyqm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2zxjnwbgh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2gizjltpa.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2fbxiugfy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2rwifbero.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqvurkre.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2rlnjqcps.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2xiybqcwe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2ykbukmrc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuaxsvzb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2djfcdfxv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gt2kasarigu.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2rujjrwfs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gt2legtmgkn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2djxsgqsm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2vecfenap.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2pvxklprt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2zluvahao.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2mhaiigrw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gt2gfhjwkiq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2kksbzqki.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2vgrdreka.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ybrevrtt.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gt2mdngftct.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fajzyisr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2olneokjr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2dwcvfkuz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsfchcht.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2qxaspyfy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gt2xpkdymjq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ccruixqv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gt2vddmlnhl.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gt2fqtkqsfh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzencosc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2anqbugav.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gt2yhandwbn.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gt2itlqjxrk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gt2fiimjlrn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gt2zfimyqic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2ffwuyumk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlgclnbz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2wajisqex.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gt2unmzrqcc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2wncwcvkf.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gt2wfecsnoe.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gt2psquhknh.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2ethqhsya.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gt2wcfbiojo.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gt2xqaoncer.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2utmgubkp.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2oumbxbzf.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gt2uwayzqmi.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2mcosrjre.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2nohupxph.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2qvtiszmc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gt2olpfjcov.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2sddqwmka.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gt2kbuvbqzo.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2dkeceela.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gt2irgbfvlq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2eiokzauc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vreybznh.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkeboorf.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2hhfplolh.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gt2ixzptjpl.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2ntlsvgut.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckecfckn.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gt2fatltxjz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gt2oluasxeq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2necgegho.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2jzxaywza.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gt2yzuevroz.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2umykkmfl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sthovfkn.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2nwrabrwt.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2qnaudtwf.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2rklkebft.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2eaqjxkhm.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2plsqqtfw.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2uchkrheg.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gt2keizchly.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gt2szkwljip.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2ulwdqsfi.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2hfjoccrw.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2qpwlxoyw.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tvrjgmon.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gt2klzazvtq.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2yacepwxy.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyuunbxj.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2gedaukwa.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gt2kvpeorpo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2iuqxzupi.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ifvvtwqn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2aavdjfnt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkgqqznw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmsnwuad.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gt2yttxxhtm.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gt2lrfujhdb.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gt2hbkdrdnj.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gt2hxfahapn.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gt2gextfktp.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2cbbxzyma.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahuxslvb.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2esukrcbf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtzckcxo.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gt2zlnfpiug.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gt2nrqfrfpd.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2khjqsuup.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gt2frddfmti.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2wnfhoefo.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2bllcwnba.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wbkoscns.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2dsgswhfn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2dmitpuip.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gt2yrbnbxwo.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gt2hhziasqi.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gt2akpqpzad.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gt2xzzezegn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mqmpiiid.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gt2savmbfqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gt2cqndwtce.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2vzfkaryq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2ahmtffxm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2zlkpaaxx.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2spicqpsi.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohyymuzs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gt2nwoxquvb.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2zchwaqjx.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gt2cvmwlmqx.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2ebnpbfkc.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gt2lijazdqy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2mfbvgvwx.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2tnqwmuwl.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gt2lndxbatd.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gt2ncnbbhfs.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gt2pukeplnu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfpokkwr.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2seaaegsv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2kxvbyogb.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2osoglkql.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2yjcwakos.html


<!-- 参考信息 -->