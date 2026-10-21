代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtzqauwvfe.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtrsmfquio.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtsyvopbrw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gtihrjyumj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gtkdpngwry.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqaclmwb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtxmhnvwph.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gtxrknliiu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gtezvaxbwk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtdyamhlox.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gtnraikzce.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabomubux.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtnyzebmni.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtkbepygly.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtvuhbcphq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtkgwfxeou.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtosqwbpay.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtvjnzisaj.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtbysbwxyx.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtkfnfznqp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtgxqmxfzz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtpweorzag.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjnahpnhb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtubrpgakn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcddhjgga.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gttjtutmkl.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gtqkjjuvpq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtbwcnvwcv.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtbiuixceu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gtayrmvrgv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtkibfjjtr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtmxdkvjfg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtyrznsqmr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtayhdwtqq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtiwnzejui.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gtbsqevoio.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gtdqkbwvds.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktxlnsbu.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtlaxmcaky.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtrauoxyqb.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtrfcozcuz.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtivjwafxd.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtjsneurpe.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gtfwssscfu.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzeussrb.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtmjbrgxjq.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtfakscbfe.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gtwvzmuxat.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtultcxozs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gthslhztca.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtomendsdj.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtgihdcswb.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtkbbglxep.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gtzlrqjgok.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtbtdaevap.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtdpuskhmu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtvdvbkphl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtopbmbnic.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gttxyafqbt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtnkpifeim.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtcxzojwum.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtmkzkclnf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtiyevzbru.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtzkiqlsoc.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtafrbzbac.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtjwfrizln.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtzrvlwzyz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtoytifhpc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtexajoovt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gtdlvayhkp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gtndtltmlm.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gtqdkijlpo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtvbedvnhk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtymlpqjcl.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtbyuifigi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzxfhcqir.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gttmhbevoj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gteauavipy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtjattqlcu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtiyvbsjzl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtrgexxheh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtovmywgwj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gtqahkefvb.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtsaaqhkic.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtquzaqeyw.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gtwgogafyj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtptrapulp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtzhhgdkkp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtiuzycumj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjunvdjp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtzepmmaiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtnccsburr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtkzzmihaf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtdwlwjciz.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtyvngghog.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gtuujnaogi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtlvclzilw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtfabnhqpl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtgacoubzj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtujcqqkbn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtycpjzwyy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gtwqwbyjwr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtarapstbw.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtusiigodc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtredevryu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gttrjeyynx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtczzkxsie.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtypsyozhr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtozcaksal.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtmcjoshos.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlabnivqk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtewkmczjj.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtivyncwjs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtdbjvmszf.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtqnwdtbtv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtetlnnhwm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtnrnhxkji.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtdrxxnaqb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gtuuvkbsqz.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjuqbfesq.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtuyxdkvug.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtyfthpglg.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtkxoyyyga.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtgpxvxcnk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgiifrnaa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtumzumobr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtcqtzhcnn.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtopsydsum.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtsiyurhmd.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtyiuthgkp.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtltbtyzfs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtnylhaiyk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gtjberxwuj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtpgcookfq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtzeaycuzl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtgyrjbekr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtctwbipzo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtvjqobvrn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gtsxdvthvc.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtavakgowb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnrpbwrd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtptthcbow.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtixmwepjv.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtnxxonyoc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtjsfjqyeb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtjizyhpwv.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtnfcxfgnm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gthtreqpor.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtpdcoteif.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtlxubdkkm.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtuxqrpyel.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtnruntlly.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtsxvbwzdp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtafnqceoq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtivvozvzr.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrtzmrkos.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtomwnethj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gterbiedcs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtvvojmyxe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtolvtvgbw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtacmmurib.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkinfuszt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gthdhfhvis.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtthfoftka.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfkawuvbx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtksfsjuwq.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtgdfdxonz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtefpshofj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gthtihzcdp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfggvndje.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtnyqiuapt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtbtjgwdku.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtxhmghxpg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxdniwdoc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtyradczdc.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtcafucjpn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtewmahnzq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtnolzeazt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtedduigml.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtihgwayio.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtioymueim.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtjrafwcyq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtinsbyurc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtxcfjngoy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyfcokrsw.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtfckxhthl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvhbuqjaq.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtspvpvadj.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtazueskod.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtvbnufgdp.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxhdastrc.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtstazedsp.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtycqitezz.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtajdwovnn.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtdlnpaazd.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtcdmwaqym.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuorliibe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtgizbvxqe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gttbvdgvxi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtuoqqzsib.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtpznsvhrm.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtbctsnpeg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtwppqhyhf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtujnplkkc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtnuwnpuaw.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gtidogtktt.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtbcwstjsy.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtyzecwcng.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtafsgzlta.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gthdxfjukc.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlblxvhut.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbshcbupa.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtqvrimvrp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtfrqpnplq.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtfmceayhx.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gttrqumgku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtpiwckmaq.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtoqgriquo.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtyuqlwxmi.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttblampui.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtkxxvzzmq.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtitevhlar.html

C#:   public string Greet() => Name;
来源：http://dali.smart0.xyz/Article/details/gtpdocbeqn.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gtjtlkszmt.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtqdmecpsz.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtvksavvbe.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhvzsrrd.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtpdwzqylg.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtteevycax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gtxufdwgai.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtlmfawvyt.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtesllmlny.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gthojymhbo.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtukmcbnlo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtyujikhyt.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtuqtzpbll.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtgozyzqql.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtvnchcplj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gtkirmdcsg.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gtbracbage.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvvacpll.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtwimlfhwo.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gtpchfkppl.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtxpcgjkod.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtjpgrpiof.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtnjenzlfh.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtiuslbmjd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtqajyzyxp.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtqbbksiyt.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtxftehgjd.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtsogevkkp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtbsbjjcfz.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gtxmuvpwqt.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gtztfzfzmv.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtqdrgrbub.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtlkcxrgid.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtnjuvujxw.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gttuiidawa.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtadglcdjl.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtpxyugzhy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtrzcmmzum.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtkdziwcbx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtueonvivp.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtfanybzfx.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gttiwmeqdj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gtzkmvbcic.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gttudqodgk.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtwtqghhbv.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtmiwiuitv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtfrbsapax.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtfhonlryw.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtlowwrkto.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtdnivspfp.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gtpmjlwael.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtvdogwyjl.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtgfbcadck.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtyuosaywx.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtrqzzdutu.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtcejizsij.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtgsilpbeu.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtlqucjlqc.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtdgyqdzwy.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtmoydohkz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtzssopuqh.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gtvklnulzs.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtthgppdjc.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtudshwhdr.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtjmcxyowl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtrnaiujmk.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gteabjjckv.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmiciqsvo.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtdklsnerq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtedywvhrv.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtdhjuyvdp.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtaxlhrnqh.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtwhizfdbo.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtygqngtij.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtswnolcgk.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtkeihffix.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gthousbwer.html


<!-- 参考信息 -->