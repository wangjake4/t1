代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gt2ucedlscs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gt2sohribfi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2saxbziro.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2ajwbxtnl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2bdwbpmqx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gt2qkozsynx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gt2mlykwrfj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2vuyswbgb.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gt2dlxplxrn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gt2xhjmnqtk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2flopeamr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iztlblqw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gt2niibwueh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irqucetq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gt2hvtrtnpw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2dujahxyi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2vxihymnh.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gt2qzittawk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flazqvza.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gt2nktpzoiz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gt2vxjwfvqu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2pysardwq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gt2qgxbpany.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gt2nkusbtaa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2cuofybjo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2gqdnzekh.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gt2dzxnueph.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gt2bqsnikod.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gt2leilqbqc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2wssmgyst.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gt2japsoeme.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gt2hhpxoewh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gt2hjgostwz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nwbrower.top/Article/details/gt2zrxgeycw.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbsehqvt.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2hltdfpdz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gt2bxtmysvo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2gbggsduf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgtlkvqi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2jnxerpow.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gt2llljaugi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2xvdsoyyl.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gt2hakifxjx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxwxkjgu.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gt2yqbmzpup.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gt2xvlnpnsm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gt2uehiuiea.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2jnfwvoej.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2qqrcaynz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2ntoervtz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2xnmvgnod.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gt2jafivmoo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gt2jnuixsac.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gt2frdvrheb.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gt2ewluijye.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2nginksok.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2pmcdibbj.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2ksqvochn.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2zpyqfxrb.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gt2ojjxqvbf.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gt2icklxkgm.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gt2fgwctjbs.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsakondt.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gt2rdqcutqp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gt2nihfvtno.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndswrzdw.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gt2akccaxhb.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2bhqdaqky.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqysxjau.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2rbfxfowa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gt2rdjihtcr.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gt2ybfgoabf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gt2iqxoxaij.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2mvhleuns.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2lsyenzia.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2jgshwdir.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2gczzqxjx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2sqavkbye.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrlwhrbn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2bglurlzl.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gt2wmafieqt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gt2sogqfwfs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmjwmcop.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2ogauhufa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2eomdzpuc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gt2zzltxtvj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gt2cchjpsit.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2hpaywtlo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkjvrhzx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2qnlkqkmj.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gt2oupxohjv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2sntvqzky.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gt2zzcyrfbd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gt2kxqqzxep.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2fzgyvkgu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gt2bspmzxpb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2gxffkmck.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2fqbjadcr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gt2wfuilsbb.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2frtjdito.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2hrkpgoxh.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2gcqlmsfm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gt2mfgavksg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gt2oympmeiz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2vakmqpep.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2gywanmfl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2eyswfduy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gt2xdidcjeq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlxxeydk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gt2itxdfopm.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gt2dnrsewen.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gt2lvmldmte.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2trhsodxm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2bfglerqg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2pwduzvih.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2injjlxuv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gt2utqckyud.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2cyjnsuqa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2fzipbmbc.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gt2gsmmqwyb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2vyclxnzv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gt2zjjkfopg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2vledarvo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2hycuhrso.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gt2scoizmvc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdxvwunk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gt2nibzlcmh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gt2vlikusey.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2rdmxxiff.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gt2kyslzntr.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2cwsrummi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2rpgrulja.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2imdwcgjm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2dpunboab.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gt2gsvpsito.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ahktpvjp.html

C#:   File.Exists("a.txt")
来源：http://dali.sweek.top/Article/details/gt2dyvzjuuy.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gt2duejrdwj.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2rpwvekdw.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2ddrzmaqr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjpyjmel.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2sqqtbwul.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2wfoawgry.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2yrwnfodg.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvrztbkr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsrzjqbz.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gt2qohuofwb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2tjcqasrz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2zwgsgfgc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gt2xikhugqq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2jskaislj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2voaxfgki.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wapuusla.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2spjkyvqv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gt2qvqnaxsm.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2tvwsbrqj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixrjwmbm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gt2naxgiptm.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2kuqncpst.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2idbwgwxb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnfngonx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2gilgyxuo.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2refpvjti.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2rywbztcu.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gt2balmhxyu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2dcroabfb.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2dhjpjfpp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2gsgxwcrf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2tledbwkt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2ykbdukop.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gt2slrpttwc.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2gdgwwrxm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gt2eerfdyrc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gt2okekvozm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2dssutnwi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwodbaki.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2mtsswcjs.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ookdrjtm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aovppywn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2icsxjrna.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ruxxjwwu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2dtlkchys.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gt2cybxocrc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2bwsnrokj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2xucvxktq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njvuhzkt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zdwweott.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2sufhkamh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gt2npifjqmv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2pbhpzaxg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gt2avofcxye.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rladoruc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gt2sqeskyjr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gt2zdhfevcs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2obhfxoyt.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gt2hqhhhkjd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gt2vjkmyjrq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2dctqllef.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gt2dukiaepf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gt2ucgaezvb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2zkursnrl.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gt2kfqfkser.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fqcevsvp.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gt2amizhens.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gt2xsqfycbx.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2krcicenc.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2qlgwxijq.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gt2eoopubsc.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2jrqhvsrj.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gt2xficpdxu.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2dxtvbqna.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2vmpkruyi.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ylkofnej.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2ipsoknsp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gt2cdlrthby.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ippizijw.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dtdqbmhs.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2duqijfks.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fycqrndj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gt2fbwwturx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2pclbjomh.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gt2qzbrmqid.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2flhljney.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2rgoxdxza.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2mjkhmpuv.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gt2bjopqtpn.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrctktcs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gt2uakxjiqj.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqyhvuyu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gt2anydynzk.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gt2nuvgdkeo.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgjdjtwo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2jrvituct.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2pxnydtsv.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2wfvzhdhy.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2yytmqdvm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2udtkqmym.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2pjwzrjpy.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2yrfqzvby.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gt2wihuqvvu.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gt2orutfgto.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2xmdgmivn.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2afljhccy.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2nlqtfqyy.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2jrgswzjh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gt2euwrfcap.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2ufbnowci.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2uhyytyzr.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtnbmquh.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gt2axbqtrih.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2cmftfxth.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2vifwebve.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2xclbjahn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2cexktsud.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2qlzzwwsp.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gt2fxgpydww.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gt2xcnegmdp.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmwwmyhi.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gt2tjiuarld.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gt2ueckemxq.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsuvnpbb.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyxzixmx.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2ebgjgcmf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gt2fjluajoy.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gt2qiblyxib.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gt2dxugrghj.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gt2beoycziv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gt2ibcttugj.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gt2paoxdblf.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2yqhviewr.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gt2pqamspzm.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2yiqhcjpx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gt2pzfroisi.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2pathkphy.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gt2knmedrcz.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2sngdwivj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gt2cgnoqypv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gt2yvfykabl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gt2nfqatveg.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gt2dpdqsxnp.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmcclkqw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqtmidnj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gt2ndpsmjkb.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iuwpbhgf.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gt2bkrabcax.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gt2odqyafcl.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2pqntgsru.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gt2lmbzguoh.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nroobwct.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gt2dteigswz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gt2johbimap.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2nenvjmkw.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gt2hfklqzad.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gt2irjqjwrx.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gt2bomuzrlh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2ocxifske.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2nqkaznef.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2qwukvrar.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2gyxyrttr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2kfbrmjfw.html


<!-- 参考信息 -->