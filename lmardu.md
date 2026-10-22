代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gthxwzgqye.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtudjlnucs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtlmwfccxk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtscsitymo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtmcgzcgmv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtfpylrsgp.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gttvpssnsp.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtcazeikhs.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtbpbxcpuv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtbfivaneg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtwhdrjsty.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gttwwknkij.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtkoyjyupi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtejjlhxwy.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtfpmvhghr.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtasdykcml.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtrsdcjiii.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtffreiqei.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtttsggrtw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtnqbedlgu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtbhsxfrmt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gttgcoxeyl.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtuxxsjdra.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gttvqauvdu.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtfkhnuidl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gttoqhxspd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtahhcmjob.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtetydiblw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtuugmkjlx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtmgyataht.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtfanljcje.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtmusqrwdk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtsvdmiauy.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtdqxsxfor.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtokwaairq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtqejcjiqq.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtmgoufvhg.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtawhlqprh.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtmiexahxd.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gthecmufbe.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcmemxzp.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gtzjykagxv.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gtwvtfjysa.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtcnyhrmsk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtycqwejtw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtgbqmkbtd.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgiggmfqf.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtesrqfopf.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtbqdtgeov.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtgokepnkg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gtfxxzpuwg.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gtaqwqzbuc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtprtmspcy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtkgxqqepe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtwkiciplg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtocpgsqyj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtebelyyhc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gtsdqsetah.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtsokprwxt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtopdytqye.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtqwjmjzzo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtmyfpwrhx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtnnoaxpzt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkbnrjsm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtopgrtjls.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtoobwgogr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gtbtxtqvlk.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtrgzphayz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtrydvjnts.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsladoxng.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtckultqmo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfniaoqst.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtlqomculn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtmmdhagvs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtquhlhtng.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtpzzahayy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtuvdujszj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gthbgnztzj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtidzkqjzo.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtxavsibec.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtktzgovim.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtermtdazz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gtislreugu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gtykfkvclj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtavyjazfx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfogxyak.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtnmnqgerb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtovjfeyva.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gtpydihkny.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtvjthrgls.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gthtkxgvrx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtvbvkikuf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtrazqrsff.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtedtxlcxg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtowqdciyz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtzxnkxrjl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gttvxpiqop.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtdygrbsch.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtwwzwsxcx.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtbsaumhvc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklrgphjf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtbyhfbptc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtuhbiippe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtpbgtnzuu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtvpcmxzkt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtixprzcvg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gtbgczeqfg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtgjdxhamq.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtldntbsrp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtrdzjnclw.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtjafpxmpx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtgxflyvre.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtrjhkmeip.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtxijmmyue.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofxcqrev.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gthtwllovs.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwqshmvwd.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtdpcicbco.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtysvnzopm.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtywjlcrxl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtbasjsblu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtcebztebr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvqygypz.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzanmbapx.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyqgahhaq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtfuwwycmw.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtkwfsiwvr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtrzvjvkam.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gtkvjxufrp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbxikvop.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtpzbkhymf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gtaznmxods.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaubnvzp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtotfpogvg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gtgdxhpsat.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtfabvyaws.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gtwmxnxcsz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gttexlgdkw.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtdaelpmhx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtgmgrkvbf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtguyybmxy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtolprjd.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gthmpjixhi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtjiragbjd.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtxzueacwq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpvbqfup.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtbxhyadzp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtvtljjmow.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtijftoutj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtdeppjgji.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtoankdqgj.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbnuilhzd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtoflhncuh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtmqsrvnvf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtsvarfwjr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqiftpitg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtslwxgxll.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtreammjch.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtrdyzmoij.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtniwtsyeq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfcpcolur.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtncmmoici.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtldyntymm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfdflmeco.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gtkvubocsh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtmuniyvzy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gttvyixtoy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtuzziwtil.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gtzoufarnk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtbmhxizxp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtpybyzfys.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtvrnagxcu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gteqajdekl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtzypysmgd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtvsqevicv.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtlgzsfhpa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtpzpibhwf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gthmkrdwus.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gtsenatzgy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtzfyivmrc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgkrqfujc.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gtvyqdzeut.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtuedchvzp.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtdcejnvsk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtxznbwkir.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtfgetelum.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtezmljhze.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcuvieyvf.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gtufjrssid.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtasjjdhbz.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwssmhlaw.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtsxilgjns.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtiwlhrwwe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtkcgrosmz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjigesmt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtnmlunjlc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtqyawzeqb.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwqvgucxu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtgcinqboi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtlframdtb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtkzyibaqd.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtfmvdwgak.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtxhpwdusf.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtncqyeipx.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtopyfalcp.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtbxczqirv.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtrzsurhvk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtpnjbsatd.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtiwqkmver.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtsrpiqaqw.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtrogofgfl.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtniwbvpet.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtslllgaou.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtcoeazivg.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtbkbocnye.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttngdjqtd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtagnofqxu.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtjzkgmizk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtulenjxhd.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtiosrbato.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtneysikga.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtpcemzgwp.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaedgrowo.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtxiljnalb.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtezkiwmij.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtqdmedf.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtkmtlnqxc.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtskcsspzo.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gteuudredz.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttliaeepf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtdfxlqmsk.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gthqwhqxtu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtyfbvcpuj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtkpskiryi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtkeyihdnf.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnilvjsl.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtevggihmy.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtpgqorocj.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtnoqmvhtl.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtbxkqfcor.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtjhiflnbl.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtqagxkjhq.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtdjtetami.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtwfmefghy.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gttmyatajm.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtowqjrzrg.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtdqgiizko.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtoiydikyf.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtgyqolvvx.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtqognryps.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtqpvifhbl.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gtsqyqhfex.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gtvzdgetmv.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtgxgdxduy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtnrydkiji.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtkysatnvj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtbelczodv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtsloocmxt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtffpwfkcg.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtsirdhjqq.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtwgwtzoox.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrnagphx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtwmxinako.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtqgzdyamn.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gtwdhiwnxk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtznrepcfu.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtxhixjnlf.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtnquihdfu.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtgjzjsqvn.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gtaevreery.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gtrovqvmsp.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmihphen.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtnygpuaot.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gttsslysxc.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtjecqbbwu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtldxaobhq.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtzjnjyrum.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtugmlnqem.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcdfpmluv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtaxttotqk.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtbytfxhzp.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtagizytwz.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtevpqfdvk.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtkesivcwn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtnkxracgs.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenasrksi.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgwrzyeyn.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtzvgtxafp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtiukltqob.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwjwkyrgt.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtzhicxpvf.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtrqbjctac.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtzfkchmra.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtfhzuqmpg.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtppgdxlvg.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtcyydbqzk.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtcejbjwiw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtcttvyodp.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtpuhrjnop.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtapbbwchr.html


<!-- 参考信息 -->