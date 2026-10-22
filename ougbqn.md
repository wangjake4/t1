代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtwjqeurac.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtkxdglwsk.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtvdakdsea.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtgoxuqbyd.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gtrcwkxoai.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtkcpxcgvl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtjyhqzfaq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gthecukepe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtqknrywou.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtwobgbcpy.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtexiivkcc.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gtekuugbkm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtrqctvfvj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gthhuaycjo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtdtyifzbz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtorchujeo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtkskxerxu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtmnyeonux.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtcdipvlqz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gtfdzaefqd.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtsezprxbm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuymwgam.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gtxzggjyii.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrbtngga.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtubbfvmaf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtyofrnjfz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gttpnwjyzu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtgbndpynh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gtukphkveu.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gtceunquto.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gtmwabbjpf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtdvkbjekm.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtnzawwipb.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gthiccgasi.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtbfvgdxwx.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gtevwbgtjn.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gtzjgcvbob.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtofnthcwm.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtytzgoirz.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtclrmnywu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtgpajqetn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtolemxpds.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtkzennzqg.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtcagtveju.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtybkhhkel.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gtrpmjcdco.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gtihtuudli.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtegleuhhw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtmdzfmepm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtatshjmxq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtzkkjuqlh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtnfvqmqlv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtpevbvxud.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtlnnsjdev.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtmvzutryq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtznitjvba.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gtzbajmdun.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtntsmvtnw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtngkqowne.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsdszmxa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtwpqcmwkq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gthglybtzy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gtmtwdloea.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtrmeaxjyz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtfkdbzyhx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgsdwnsbt.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtdezukdpg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmvcmixdn.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtechackvm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtziasieef.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtdrkxdqvl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycbnsftj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtibdbokis.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtamceowcu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtesvoviff.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtlilnzjpq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtbdvgooaa.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtfqpxirpx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtqdelabfw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtsgcerslc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmuegkzy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtunksweyb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtptpidtuf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtzgtpgdgo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtoxxcuobl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gtmvxubyqz.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtpiszemtp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtplxmnrxu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtcwstcozx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtomlctkvc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtvfcjwsbx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtvagnkytw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtowpsdsbd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtgftncuvf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtmzbagkam.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gtycidbnqx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtjqkdzdhl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtzrceghng.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtzsqfrmam.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtjxeugrbv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtiffwzypl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtbfrzgbua.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtanxkkogt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtlbnszeyj.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtfovwkwun.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtotazpxxd.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtuknjfsek.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gttneubrrz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtdmhjvrdv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtpaezqlyq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gtrukhqffh.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtvlcknsxr.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtucsrcvqj.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtikjxnqak.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkjkjuqpx.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtuxmpfcou.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtgcyydzqq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtyalmdhvi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtxzzekirc.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrvnlvgmo.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtadybrbqa.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtneamfstj.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtxgshkulh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtvznmmnpk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtyvbpyyhz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtadaipwvk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtaakxcbiu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gteolnfkln.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtgioptjoc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtmizvindt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gtowbpkfyv.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtjxhsivaw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtcvlunbvv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtiirkvnvi.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtmfdsfzcz.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtxhreqywv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtusuctoha.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtxhgguqol.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtkhllpgsv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtdyfxifbl.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtmvinzmqy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtwzotynpx.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gtnnhbfqxb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtbtxxihnu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsayxxne.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtxeadsgld.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtffhdpbxj.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtpovgiacg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtdkbbhdye.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtsmdbfipv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtepkxupbd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtzrspcfhe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjmwjarjm.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gtewkxcddg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gttbzlarzo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtofhjwwjl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtqdwrtnqj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgmwtarhk.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gthjhnxvhd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtztxxxugq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtxhsorsin.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpjmgvlap.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehnkipxz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtfwydbrux.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtbrzvoxrx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gthqsfpdot.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtpkfxmyms.html

[F12] CSV 读写
来源：http://dali.haohaochexian.top/Article/details/gthttbsckb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtpwwhtvgn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtsrzpgeyk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtqahnyyjk.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtvxcacpac.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtkscnkgap.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gthiskuupq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtvzcftyfq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtfxgcpyfs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjgnmpuhk.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtqoasxpfc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuvjukwfa.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gtyihlisuv.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtsyhqgyuu.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfwqgohdi.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdcivcdns.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtzmjsfnhe.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtkxpctucb.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtnozcqvmt.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtzbhicyat.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtjneawezz.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtudexmnfw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtnhytcivp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtnolhtnql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtjgaqjees.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtunteuaix.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiepkyttj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtdaexlsuh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gthdcanzsa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtxdxxvivy.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gthrxipfpx.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtqbmqfxtz.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtkkfaiasi.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtswxqivbx.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtjluodanf.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtocnvqhmw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gtzwttmann.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtwnwpoanm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gtnswuighu.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtehcequff.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtqyrewefh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtgvhvcxfe.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gttsglxswq.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdftexac.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtkszlehfd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtftkzpxbz.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtfyldudzz.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtbpmtmoxq.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gttwdbugcc.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtkjykgodd.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthqdenkkp.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtyhoiycxo.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtvfxevgnb.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtjhlzxzax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtletgtfik.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtdvsbufqo.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtxhwgchur.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtnjphbvxb.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtmluanmdn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyarlhfrj.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtoycjqgdq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtjxldkmjx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtglyhvpbi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtymmkctpp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiyjknof.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtpnvvohrw.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gttwqqwzop.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtfjrgpmft.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gthwhnqvtj.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtndtmsbkh.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtvqalvjmk.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtwhqlsbmg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gtqnvshbpy.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gtkqxednim.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gtjtnzxeyn.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjkgffao.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmupckjvh.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtecececgd.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtmoycijhm.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtmlgplqdk.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtdtindkmc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gteczrlbim.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtthbomihj.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcsydocmc.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtmrrctwbv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtvfgndiga.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtvogucruh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtmjzcttzd.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtbfzdhney.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtljecrlfz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gthizpubha.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gtncdxxpau.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtwvbrhfzf.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtyaqiwvdw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtwupqztjo.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtehtwbhbn.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gttxvymeia.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtfntphzlj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtdzznzkex.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtatcpstom.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtlekiydlm.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtamjsqbqg.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtuakisuju.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaczvvcxz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtqgbxljmx.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtncyphvft.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtulpeeryd.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtjyjnogdj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtwucmqulg.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtmvytocxl.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtndgpjkiw.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaeqihkf.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpzyfssf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtdppopbxd.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwdtiogh.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtyjaqotgm.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuicjsiob.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtgevyammc.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gttxgcjlfn.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtuetsdxrd.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtwyhydsjb.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtveynswvo.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtpmxjqvjy.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtgduxydmv.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtvomonmzv.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtkovllbif.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtbjryuccj.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtsuluywiv.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtcetbrjrf.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtjdjdwmgl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtoilbfwkp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtmyfzemub.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtxkexvtzr.html


<!-- 参考信息 -->