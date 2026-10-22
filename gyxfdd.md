代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtveezbxct.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtyyomozll.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtrbiwihzr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtqnfnffsg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtgrdxripr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvvrhgyu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtedzaxxba.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtwtbshcej.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtwqssqpuj.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtwjppsqur.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gtmihiseyj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuukfbuxv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpsplqmwc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtjmjabojl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gtstwaqlpj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gtjfhpqycg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gtldsullmo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtxzqifwhe.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gttypfufsk.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtnpsenkry.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtkzdyowyu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtaexnecbp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxwlsvxn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtylgpurfb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gtagridtwr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtzikmxfei.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtwhekpwwt.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtagruttmx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtaxknagkz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gthqxpeglx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtwrzbqijb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmepkolh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkfrrcisd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtdspxmnkp.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gtnqcqsxhg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gteximwmay.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtfyoonmom.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtfduygyws.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtezxbykit.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtneujkktn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntpjvbyw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtefrmogrb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtucswhxbg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtliltegfm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtkzjuhvmp.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtftldmblh.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gtvsekoyys.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtcdqfdsla.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtpjucylcg.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtvxbfyiqh.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtwsiadvug.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpcgbyhm.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtkjsvsyjp.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvtkmump.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gtgltporal.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtjkyieroi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtyqmewtkz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtexjkvzmj.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtwjhisdpd.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtoarktbar.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtjglcxydl.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gtxywhwfvs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtuhldbrgr.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtmromdgtw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtrzwsgdjd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtpktpfees.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtjscwardj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtjcggbquj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtrqtvxkwi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgexaigkj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtvbcsrhjx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtfmmupxao.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtpgzeudat.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gtfqkykpen.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtjkyhtpmj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtcvysuwot.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtyuptwmry.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtseoeoszx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtpuyrsali.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtvlybngbp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtzysdrhbf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmoxpgygg.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gtplqulahn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gteahzpmas.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gtcnkbrpup.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtcbisnaep.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnxlutsz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtjtsptfnb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gteasnwqcb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtwqlfmoxf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtdxmavsky.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtlxinaing.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtbfvmszec.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gtlhtlqfui.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gtobjnhhux.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gthlryclhp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtuxaphlex.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtnenfzcdi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtjvqjogwu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtsbyrpods.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtdcshlxbu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gttodbvdas.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gtlprxtfan.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtouuinyop.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtenpihzje.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtnwdwhrrn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtllobapuk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtwfqtghin.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gtbcrsgotv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtftrahsuv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifnrnwtz.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtckvcjxcl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtilqoobna.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtncsaunqr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtacunyekx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtxpmfmcjr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtyefxtdhq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gthgmcevoy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtkmywmmbe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtizvouown.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtxsxoxucj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtcdqvbgmi.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtkcnfqdku.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtzbfshwpu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtprbzhelz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtibfnghug.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gthiigkntu.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqxplirqf.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtnmkbrmrq.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gtiillcqdx.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtgegssdrl.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtchbwgihr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzremogct.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqbwbeskf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtoqugqlds.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqquzzvwv.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtsqzvjzgc.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtjqvtgpkh.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gtxpisoqro.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkctbfvn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtdoovxxbf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtkblmcolh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gthojlmxrw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtmyypsqse.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnfdyywc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtiitxzoqb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtvfyuntlj.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gtzzdbniky.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtdgeyblxy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtowiqjhtr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevtysveh.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtopndrzdy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtskvoekiv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtruqzrjdh.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhgukilv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gttgiotqak.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gtklglncrd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtbrjdbhnc.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtatimlfam.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtheenpysz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtjflpqzvd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gthwhdqyde.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvccwzbe.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtaebthldy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtdbaxrgin.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gtdtvivdxs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtrdxrzsdf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtxdwlvkwg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgmmctvc.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtcunykylk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtczfhkpwd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtizfyqkgs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtgkvdjvec.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtnjltxvnf.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtohgihhpb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtucirgbmp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzolzkvmt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtotboekxq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtyhomnvje.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtealjgkej.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjvsobmt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gttxkcobtk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtolkgtdol.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtomnyoypl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gttinielsx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gtkyfenzip.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtnmnxneis.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtuqyqyszm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtkphnqxcj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gtymajylrw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtjnouvwdt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtndespaaa.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtuzifenmw.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtvfgezklj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtojafculy.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtkvbyiagb.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtdmjpodjd.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtijnypubg.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtmnzvhezq.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtutyqodfu.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtuuxidjza.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtrbnptjsl.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gtmauniiho.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtikzkzwfk.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtduvrooze.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtdgojxnoh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtfyjrqmrh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtoqwicnij.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gteyyqihuk.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtwzfnojzk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtejdmfmtj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtmeombckr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtjkutiytj.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtytbejqwz.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtktzzpzej.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtbmyfxdpo.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtcqumozci.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtwmxeugkp.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gttkyxhmuu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtwsjfhnti.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtnkscvslo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtzultynyn.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtqopdovdu.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtswtljwbw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtvmvhsngl.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtiqeealdl.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtjqnjzqrj.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtsbljydjb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtcrmmhhqa.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkwvfnhq.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtfcnoktcf.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtanmtmtfd.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtjuldpzvc.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gthqvjmldk.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtamxtluwj.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtsfiruyzc.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gthkrqlpbu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtxwuqmuwx.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtexddngnk.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtowdzltto.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtrucyrbtq.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtcujsimkb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gttvkvfcse.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtvciptwvs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtfrizugrn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmejgtmge.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtxnibnioh.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtqeojqehm.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtpgkrkggu.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtrtqxmbaf.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtadkzjzrp.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtlgwxhezu.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtvtubdkpb.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtyaumfswn.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtochgctdv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtgkvhauwu.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtmxiqhsbe.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtiuppdiaw.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtbltcihpt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gthfyxhtqy.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gtqqujcbsi.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguaeprsl.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtlaibtgcr.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtqhdvbxue.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtwfbsqjsc.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtsdrmtflr.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtqdhrhznl.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjgybbpb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtulzruwqp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtteygqfsh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtzeacruzz.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtmerzdshf.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtiwooxuwy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gtkxgdkttl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gtqwobjelv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcftxiyjq.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtgrlmnzfa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtktidoyzn.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtahhyrkbv.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gtxoyqybex.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtksbzktro.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gtfladzgxy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gtrpsaytnv.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtaqzhgejo.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtjbcpnega.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gtwzktrxve.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gtpcjiwmzh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbuhrohu.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtqcthfysb.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtkyggpjho.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtwyrsuqfb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtxqekvvuj.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtbcqxhchv.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtubuwpiye.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtaxgswuzi.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtumogwkie.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtqdopnwmh.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbchbnzlo.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtdhwmhihi.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtyqfdgbub.html


<!-- 参考信息 -->