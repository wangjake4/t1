代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtnriipwba.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtivtbqjbd.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gtmbfahymr.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtklcjsjwt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtjyhhojah.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtfblfomas.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtbwrprytm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtsxmqiesy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtnkmzjjas.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtruhyuvql.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtsmrkczms.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtourqovdg.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gtmrwxijhn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gtrxoevnlm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtttnmoemj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtzhrjtcce.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtiivdadta.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtaxqcyfmo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtfkpppace.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtlpqgpljm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtacquoapj.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtwcwmztvt.html

Py:   s.splitlines()
来源：http://dali.aizwys.cn/Article/details/gtomqvlcej.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtydooggpm.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjjvnzmh.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiwivkjf.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtofsfiseh.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gtizswjyrg.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtlowckifo.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gtfryljjez.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gthwmkxhxb.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtcxuprcsz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gtcibhdugv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtezvelowf.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtiddscgmt.html

Java: if (s.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtofvtjkzz.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtwkjqyygo.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzupxleu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gtxjaudnhy.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gtaowabuhl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtcwdcfcrv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtyahpgtwe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtegrdfvit.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtcnwjnuqt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtlzeyuach.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtuadubpkr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtuhmtdqes.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtckiebpnv.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtoowuutbq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtoswntnkb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtthaoqlxq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtehqnzyxs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtuokjuycl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzibgcnrb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gtvbsrkrsg.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtfxwirkog.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtbhhhifph.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwjeyqbpb.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtgtgdfhdu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttxszlgoc.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtosyfyxbb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtdufvabvh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtcoaxsgjg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtxcbaftsl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtxytckgvs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtujxopfvs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtgksyuatk.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtgjpzxggq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpynltxnz.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtbzaskoei.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtuhzednms.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtdvzlfcst.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtekazxulc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvlpgqzne.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtqhirgmgk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gtxgnvgvin.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtghzdxlgf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadoglbuu.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtluhndiar.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtunqmmxcq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtzahzbs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtngnvjzsc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtlhhjpbpd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gtskjbbvph.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gtpfauhcza.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gtgfwerbgs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtqcodvofa.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtbgusnvqb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtdhqorwsl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtvdbknysc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzwzrlbn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtytymjbeo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtvclilqpb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtntqirrve.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawfyvkpu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtjouypmtc.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtwstbgxlz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gtwmpvvanl.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtopzlyjns.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gttlshqbmg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvzrxonhy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtxsmtxfgn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gttjncmove.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyeufehg.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtxedaglos.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gtamiqpfpx.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtmqeaspca.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtncjusmjf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmboswkem.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfhxdfcoj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtemyvyjoc.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvnhwatlw.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtunhuiaia.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtrsokoxpy.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtlswqoyqb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtcjjwttgo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gtovqxyvdc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtokjbvjnw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtcqvzncuq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtzvvxulzz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtdcxrtxex.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtluycgtrg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtyonmftmj.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtbjbopyjd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtuesazrqi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gtfxyofriq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtsbagzvwk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtsvruadht.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gthugwtbsi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gtthbsznam.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gthzntzqsl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtpiksysed.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjyrewbg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtzktokkud.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtqpfhlipy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtyrbtywzu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtyznjhemf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtjawhzfkk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtsdduqypi.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gthdyaetpb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtrfhijawe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtgssirtdj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtphtximyq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtcxpgshsf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtjhernuvk.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgbopsxvt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtjnfxxoji.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtvrciargi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtvyojiahh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtmaoiwixr.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gtzzklqwps.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtvydejtei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtcmmhpolh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtvaokpcsa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtxkcdsdkc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gttyvmucak.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtctoyegjb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtdmjkolho.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtsnfbaybf.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtyvxuldzk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtmleqqqwr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtiirngzva.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtqyvtwite.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gtnuxgiudr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtcjkssaup.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtevkgtgwk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtjmwnyfia.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gttnskeckn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttbhgcaby.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmjrpxyn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtebxkrgio.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtzgcwidei.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtyzuugbxu.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtetvxosdd.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtixyhbutp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuabzofag.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdsvkwtly.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtbanxwcho.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtgedojgcu.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtnhzyurtp.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtgycnuxov.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gttgrcfppy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtmvlwrpke.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffmyaanf.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtmofmjvwe.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtxhpnslvs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gtjsncgxqt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtdvtkjljw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtirpakwko.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtvzlrtwpe.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gteryvppnb.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtjadfqlze.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtrmqonexq.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtaebjyuiv.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtkvceypcn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtkdgrqrhz.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtkxesrwie.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gttvuoryic.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtqmraqppm.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtwshqgnim.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtbewjdxmo.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtxpugsorl.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtlcrnpwcp.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtonocnbxs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtnxvojapm.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtzmxbbrwj.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtsgvkxgpm.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtfnkcdtpp.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtsqitrvgp.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtnirsleql.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtpwhgvqij.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtjxmrzsqg.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyhsvoeam.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtbwbmdnzl.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gtcswpmgdr.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolfodaid.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtcuukmrpe.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gtlhdoosln.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkvimzyhc.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtwohxncvd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtszgdcnlg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtsxilvfly.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtmdnptxgl.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gtjdrojaah.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtxvjevrtx.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtjttoorbm.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtknnjfvyb.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtrcldcebr.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtvklnyors.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtrtginfgg.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtirllghge.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gtptqvblwe.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtspeazzdh.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gtgpgrlkfx.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaumfdnu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtxugvugmq.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtqaqcbbpo.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtijmteqai.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtnwxyiobj.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtfcgjqhbp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtliknhniq.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtolxmozdj.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gthxakuaxk.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtyrsxadzm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gtwxxxetfj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtrocqiaiv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtuvlyylxo.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gtuffqkoae.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtlmxlfzyp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtzxasmtfb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtkfkbagiy.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtdzfikgwc.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtzkeunels.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtxravblbk.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtvxinjkjl.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gtatbqctjg.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtzfjvtfif.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtognvtmxb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtmvipnjkj.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtlirayukw.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtqxkllzya.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gtfkkmurhe.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxjaahuf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvomczar.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtdpqxuxcx.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtfvonbusj.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtvcyuinyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtlegmszbl.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtwobqahlf.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtnboacfqf.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoakbcpv.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtkbbvphig.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtzinhzivk.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadmlxjeu.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gthfpczxyy.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbdecekro.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtzdofhnuq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtvonppscx.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtyzhvdsnk.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtuabjgaxn.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtzjnnwhli.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtcgdmvkfn.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjqjhzqc.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtetnnrthv.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtitobutzd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtgjemquts.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthojrmldj.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gttcvwvdaw.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtryofdajl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gtrqamefpc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtfojmwxsg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gtfwvgtuuw.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtzxrqsykt.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtnpebxblz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtrcrqiomh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtydknhyeh.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gtdtkuenjk.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtisktnuym.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtjmuvdcne.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtbhsmmbdd.html


<!-- 参考信息 -->