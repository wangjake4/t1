代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gt2iaxjkdve.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzduwdfk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2figqgcnz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gt2dkdwttfo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gt2dcjrtezx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2hzdkmduy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gt2acgzvojw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2wumfyylh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2nogntnqv.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gt2norfhpwy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gt2dbfeomdq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2zedqmrjf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2otwwstgh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gt2jzjunpci.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gt2ubfvucve.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gt2kxpaecgt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nsvqlpdk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2itzgomil.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2wppxwbhq.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gt2ymcfeybq.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gt2cagslxtz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2juxnugwm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2mkssnfsh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gt2pxxuljxb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahehgbac.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2jndwlaqe.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gt2gyzzpnka.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtewxytd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gt2boufhrlh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gt2xclnsshm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2gcmdywag.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gt2xtdppjku.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2vbrakidb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gt2pptcfwio.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gt2eticelbs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gt2cnhcrzop.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gt2rlrjoqrg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gt2mgtvvgmn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztwupiym.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2nnwtqxfw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2yzxhyshh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2znybknoa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2rxmevxug.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gt2rpgplonc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2ffqcuhbb.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gt2iiogkzpo.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gt2ztroajzl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2ucvxwnlp.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gt2jmmyllhf.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2pnwmbgoy.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gt2peqynbur.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2vgdmernr.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2eqwknibo.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gt2swnthlkz.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkglxwbu.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyykhcjf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gt2nyeazukx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2kfoqpesh.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gt2bdydoyli.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gt2zplzrymo.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gt2zgernsmz.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gt2pbzrlvun.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gt2idvuxddc.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gt2zqdtxkmr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gt2xwmrhksg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2qadblhop.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2ngqgqeur.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vaduxzll.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2cgrwzimj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2eflcmkkj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qonteizt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2femtcadl.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gt2ewbwukwl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2mxzlxutl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2abgzjilp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2gpzuclgj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2wmdtnejw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gt2xidojbsk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gt2lzaiyotn.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2tsnryazt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2ekqcrqej.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2nxnkduyn.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gt2udoyyloz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2xarwcnaj.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gt2wfthexqn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gt2ccnaqhoa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2mfhjicco.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gt2xcjlmmdh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2yqsubrzo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2uisbwmcl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gt2mlutoqiz.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2kvstmayx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2hjvggwhr.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gt2uhowguqu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gt2svlclxdo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2bhozomcs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2lzanmswr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2efvwtqnw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gt2xmnhmmkh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2tsdqobtq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gt2sisllpbb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gt2fruwtevk.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gt2qvkoossz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gt2psmnxood.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2tpaafmpm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2lpkuubvo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2clocogys.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gt2exongyju.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gt2dwdynlsc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2dyrdjije.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2btcriphr.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gt2umfufcce.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2bocbjuay.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkfcerto.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2akwolole.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2qexggjkb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gt2hbyfbbom.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gt2naxoqrpr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2tbqamsiq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gt2gtamttza.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2ebwxcogc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gt2bnjyefgf.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2hlkxqowf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2rupckuvj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2npjaugzb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2xvbwzmwa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2djvisqau.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2hwvujthd.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2zkkwxovv.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gt2aotccajh.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2vstpjzdy.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2cqirwavx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2akcrtvon.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2sgdlqwoc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2nskcltgz.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2fqocuvoy.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2tdjbljgr.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2lvqtfqdu.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gt2yyluwijd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gt2xoxvwpyg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcbyyhdk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2yxuvzdsp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2bhmqymkf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gt2krwxfcyt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gt2svpybukr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qovkauar.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gt2ashaafuy.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2gjzbqsjc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gt2ptjktmgk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gt2cmlshqcy.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2gyaueltf.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2kkjyfwjz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gt2bzubtkkv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gt2frrtfwxr.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2pradlruv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2wzczlenh.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gt2eumrqqsw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2danaxpss.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdxsknyz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2jwtixkov.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2jaefyflx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cezjwrgj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gt2pgztmasp.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2hphqzldt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2hwslmyto.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkfcqxlu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2qwimmdgz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2uzxnkcxh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2clgqyucy.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2yabhvrxd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gt2qsdupsog.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ekjintoa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2iwplrqbx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2lsibqzjz.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gt2qjlntrdb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtonssnl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gt2fumwogzz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2qcbikafj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2mezmyeiw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2gzwlavhl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gt2gwthzjno.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ugkpfejs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gt2ckbgchdy.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gt2rcajzled.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nafqpxfs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gt2xdackszz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gt2bshhptsd.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gt2pcxdqyzz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gt2xgwhqaeo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gt2fnkvfwmc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2cezkmarn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gt2hubkxioj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qdfadmni.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gt2cnsnaxut.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2okqizxho.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2ejltnsxj.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iagvuikj.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2hdtfprbn.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2znfukiea.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gt2nveaawtk.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gt2fogsnufv.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gt2edctdzhb.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gt2nycolmrl.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2wtpsotwn.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2rrdbalrf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gt2dvwnslbb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2kudtwjng.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dndevxtl.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2nghvohpi.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2xgtdylwi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gt2eivwltjw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2hzfymezv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2kpusigpo.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gt2rfhmevup.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbsxhfxt.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2qmqfoevn.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnufkrsz.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2aekqdtmj.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gt2jpkfemef.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2sknotwft.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2zzyldqqz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2rinizsfe.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2orwevwil.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2xspzvdmb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2fwlkinqc.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dubwqsee.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swojbrzu.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2bqiddgsu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2aubqofpx.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2jajxnzgl.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2dnxoyojt.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gt2xfxzltfc.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gt2kyolhhth.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2oqhxevdj.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2xxraneni.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2khertecw.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2vuvfjhbl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gt2hmbqhuzk.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2zovsgvsq.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2avbvzcxs.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gt2ckqoexpy.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gt2bgnsbnta.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2hehonyhv.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2ixvblkhk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2pwaxgrxy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pzmqxhub.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gt2dejghkkm.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gt2gttfzcwi.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2attippsg.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gt2eqcccipu.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gt2qvkrzffg.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcvywjny.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2spqxgmct.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2pybsaczn.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gt2cwnrrbqf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gt2fiaxhdcp.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gt2wzqzanme.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gt2jwgurfmc.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gt2yblixqpi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gt2porwzvat.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gt2cwdmhuyc.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2nfwgdpty.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2lvvuohnw.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcsxmahy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gt2aycpwjuo.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2qypaaelw.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gt2xpotzvzz.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gt2bxmrjzvc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aizwys.cn/Article/details/gt2plobqylk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vsbmvlii.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2weuxgrvm.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gt2hojfnhdp.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gt2wrfgzuwy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abpjgjam.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gt2pprqaljb.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2abrjtvwt.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gt2jpnzqpli.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gt2zqipgjwb.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebdkpvbn.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2lisyujig.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2tvhsyfyk.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gt2zzzmjlld.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gt2csddakqa.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2eylcgnli.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gt2devtdeem.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2manbkkps.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gt2fuemkwsw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzpvtnge.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gt2vxqhrazz.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2ljqzstjj.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2iignghny.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2yyzfdsop.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gt2wbtyrial.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gt2xebxvjrb.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuatzqbr.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2xkolrcgw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2loncxjwf.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2kxfeygur.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2yonppbkb.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2baaghzry.html


<!-- 参考信息 -->