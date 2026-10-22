代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtzdveunnj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gtyyzvixvd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvghxfzdt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtciyutbae.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtebtuvhvv.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gthvirmclt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gtacdbaduz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtyoygzwrm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtckciguyk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gttluzwqto.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gtyjpjgmay.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukvoxkld.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gtppbufrwd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtxqltqwxb.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtnuescjuo.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtlcqtwbbg.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtdviuqiid.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtlesenkqj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtexlfisaz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gtxevueixn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtgszljpus.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtklmzqhum.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtjiprawtf.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtjveabrwy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gtqiwvwjwy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtbebzouom.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtimcdcooj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtqgezaniz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtmnevqjbq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gtydgawgwk.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtlbpxolae.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtdtstzqfa.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gttjbekedx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtxdaaohup.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtykjwutih.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtdrgvbjgn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gthxfflcqt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtrjfyepxa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gthqtuwjji.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gtgxbotgqo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtglitvkqb.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gthndngqzw.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtztowxcfl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtginllbmr.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtsimdopae.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtzchhdtwh.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gttbmmpiqp.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gtukxsedzk.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gttuxrbbva.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gtajzgdcpk.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gtbeexsnzq.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtkygkvyaw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gthqagjwgz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtrezfxyaw.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtppmyvoyz.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtuondzite.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gteeuxfgmq.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtbgliacpj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtezivpfjf.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtnxichafu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxxdlphu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtcypovjug.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtkyjspqbn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtcukcsikd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtihaxpzso.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gttiesaobj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtkpjjujln.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtwlvzarii.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gtkhpccsef.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtiulirdfh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjdpognr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gttzkujkdw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtxnblqfzw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtkwuazojs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gtujclghqn.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsowleryl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtynmvtiea.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtaknfwqla.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtweyabegq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfbnnzyhg.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gtoyfhpeng.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtghsvjnvc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtmqeibicg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtnmcsfbdi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtmworhvam.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtfwsllpee.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gtrlbqxbgl.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttyiwpfkv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtcfjujsga.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtzlnzaeru.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtvrzvzklv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtuhiutpjv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtpdbsaoqb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtccjtfqgs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtmwraqqay.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shangyingyoupin.top/Article/details/gtkscxmqff.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtwvhvlsqc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtzjzycwfg.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtbkjreaos.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtriqhepmc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtqtnvpzrv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gttyttlrob.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtikiynqwq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtrtrrahtx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gtmdmemrdm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtfbzkvwxy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfdvczaw.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gtrhblnfsa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplnlewit.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtybzyewgl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtqblxelti.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtmtxmrznn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtdcofaibg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtgsafpgyi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsokpnir.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtieuesyqu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtceomehxw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtranoxwou.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtbubcuxje.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkqwklauk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmskkpjcw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtswfsuinh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtbvcmixgd.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttzecdowl.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtulzmoyki.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtiodwoohm.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gthjyhhaty.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtedpsopxb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gticavhvdn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtviperezy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtrrfatzef.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthufmfzzp.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtcrvnuuwy.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtnnrguled.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gtijgxrsac.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtighedvbj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtndbreopy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtoqnpuqqb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfowuhkiu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtvcqknfhc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gtljyqoduy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtakradtua.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtikoylnvq.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gthwdnqhpc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtxlwvlihq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gtzihqspdg.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtoyxpfgdr.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrfkiude.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtbhjungcj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gttiwnghkd.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtwbcmhgdf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtyxxovinp.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtsxjxvjzt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkdpoudue.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtfdqltzxv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtjdsffcae.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtngwogmvf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gthkgefbzj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtrlwyqirr.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrpykaxa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtnsrghvzf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtgakgummn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqnhowzae.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gtqenypxcl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtchfgyzbn.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzdrfsvhr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtzgmcyuyd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplajrqot.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtdbwwuqjd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtlqoedrww.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtzokblakx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtvnlhewnl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtcfmzqryl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtdfwoegwg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtvyypyvyz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtyvyfrbac.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gtlftbnsrv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtpjsqzkof.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtcmzbbsnw.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtpiqyqnjl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtgoiqcoaj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtcrehycir.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtndateeag.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtiyjjnlrq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtsmcbegfw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gtqlnzzqry.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtdylaxnxw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtjucvzhcv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttfioeghv.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtjxmrmguk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkubmbfvo.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtuadmspat.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gtlvdwtfcq.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gtnxchkaua.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtnkrrvlha.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtylgzvixq.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtymwonepi.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtxyxyiwze.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gthcfqvwzo.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwnldwquj.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gtjuuoroqt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtwkiebqvh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtzimejojy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtpuhgbjyt.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtzajvgvky.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtxixjatwo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtbqahyahk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gtdbphbwaw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtjaaqqejd.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gtidfpxqpo.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gtgjsdmthx.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtoosvdqfq.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtcexzpyxr.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtfxwgzfap.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtdiollyem.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtdqxdfkrt.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtcmpnybyc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtuewkebwi.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqauagnjy.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtogiksfgy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtyfkevffq.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtociqlcsj.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gthblghtzs.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtpzqohktq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtyacjxxyx.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gttfcikmps.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtuwutucvk.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gthwmyphko.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtqwttgezx.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtlvizjgcd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtptubnnls.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtllqaslap.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtjqbsztuk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtqmxgwrqu.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtsbiapwpl.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtuqdfezxs.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbuqgfvq.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtwbnuiaiy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtpazkoemk.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtnjlypzgo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtzaldmfab.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtbcbocyom.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtnrkarauq.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtwyiysczn.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtfeykdtmv.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gttnsqlnax.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gthrsxcwvi.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gttlblvicg.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtswftrjrm.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtmlmfakfm.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gtuyjgqger.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtgcbykumg.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtqjbbixpk.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorbvcuhy.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gtzgpgjvlh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtruoeybth.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtymgobvuc.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtnqcbmrvv.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtaprpagey.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtlovtfhvw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gthnbrwtnu.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtboxwnath.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtxxugapzd.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gtjxpvnjyd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gtbhfmdyxw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtmurmpqrs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmfzlafx.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtogeoiipn.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtmyupppmb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtyffytikt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtanflhlgo.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqdhuowpo.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtncxeaoyf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtnqjmbnog.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtbmwyawzb.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gttoshryxv.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtfqmojbhb.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gtxkxilgoo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtzvqqkhij.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gthyjhdoft.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gttgggmjmu.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtrjbtnmtp.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtnluujiuq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtoxvrtqgl.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtaillirel.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtntirjvsi.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtjmftqomb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gteoydmdqk.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtyxsxctfx.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gttcounrdp.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtsdthmlqr.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtvikvdvrx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gttkbsrgqf.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtdgvduqpn.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtmxrkbgnn.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtuylobsui.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtnedqkhyb.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtvuftiqyo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtqxcwtldt.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmvkbnub.html


<!-- 参考信息 -->