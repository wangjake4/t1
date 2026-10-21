代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtxlgcxsak.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtzlrpfzhx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtzftaztbf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtcvpfurat.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtuxfuboht.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmcqmyfy.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtlaelziuc.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtxsomlicy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtlzrsrpki.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtvjlpmald.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gttotpgxfg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqxtirhkc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gtvuafgjgl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtjasneesv.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtfmattzks.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gtnzpjbgje.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtkhmrjjqz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtujdzgxzu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtztnfdacs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtkozxjpln.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtpzqlaxcg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtjjjpeefz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gttwogsbbv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gthwiqaylo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtwumpwnty.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtybejfbts.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtpuqxotht.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunkzzzcc.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgsipmsa.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtliyyztlt.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtpocmvzcj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyrmvsoq.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtgtspthfh.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtkbccqkix.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtwskytebf.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gtmrtcqoan.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gtddxmxygq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtykjbuiod.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtmvklfgja.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtlpaaxwmx.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gtxjyuuqlk.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtlesolxyd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gtbuvoiysa.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gtkrksbnjo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gthqblcodw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtbglzqblm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtzwgghnla.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtzujmafko.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtanwihloy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvkzjubs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtbdsxozdk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtqsoyvggm.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtxgjoocwr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtfnwybrbk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtfgwdsdqy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtqwculbyc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gteefhukel.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtrwmoerze.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtuavqeejr.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtpyexxywb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolgpvgkq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdrcgqfhi.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gtxvmowhdb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtmevfqnqs.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtthmiknty.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gtrrjniryy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtotgfiskr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtemvaykwj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtfevonyfh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtkqvgmcnl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsnapggq.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmuqufqfo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtfmakqwvw.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtyedzyhuu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gtlhyubqcr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtpxleknea.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gteuxdgnxt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtiwdaviwp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtzpttjkqz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gtaijhvuai.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gtbaebycal.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtkcooskyn.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gthunavsvt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoowfdvbs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtjhouxsho.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtotahsgpg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtzfxbtxpj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtctylxzqw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtwxshcxde.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gttbxwlrlq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtbbhcbirt.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gtlzdolhgt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtecwlgdxv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtlpevjfpp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gttsomsrpr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gterenyubb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gttioqnilt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gtbbvcvbmt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gtqqrckiau.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtuvyhfxer.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtmbrjmjqx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtfcensggb.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtambsdtto.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwklyqvjp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtecuzjkbu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtvjzldjpk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtftcliynk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtyohwcbzy.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtlzeqggli.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtimbntxen.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzftsatud.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtgvlwphni.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtjrgvwmst.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvrvbxbrs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtihbvfcbb.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmvnucuno.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtchmgoaht.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gtljvqsunf.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtbendqvtq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtjtfxqcti.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gttsxfknsi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtokvbyfql.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtgenwyesf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gtilbjagpj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtyeydijur.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gtkzrhplnf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtqaspaxkw.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gtsvfhsakk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfuvyuco.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtkxypwsqj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtxanowvwm.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtweoeqnaf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtoybhgdyh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtrisskpel.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtayitttyz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gtmbzogbsr.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gttuidakvq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtgipjpvxe.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtfqrtsnjm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtgcckuqmy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtdqbppzck.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtdvkpccdf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gtgwzdjwcj.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvpsknco.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtwmmptnng.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtmvectlqm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlbqgsifn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtmychwzfj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkvsznvb.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtnafxxegr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtrqbhjidv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtvcgvlspr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkbsilhii.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbkurlpfi.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtrwfnqhlz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtmzriqqec.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtqkepqsbu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gthdcyxxtr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkclvitxd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtysugtijh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtksvsopov.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtyhjyksoj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtvqripcef.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gthubzpxlu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtokaeojma.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtxxdlbqih.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtreupxjvj.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtsmjyilbp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtrbftaxnn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtjpalfnpp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtkmuuspng.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtffhawjym.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtcixjdmbk.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gtnymljbof.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlqiptlpr.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtfopvbzep.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfkucmxn.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjknnykzl.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtaseugzez.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gtypeybsfz.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpuslzcok.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtcheeqqdp.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtwmynzqtw.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtbweivdok.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtgrwhqycz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtxcuaygwz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtgsrocgsi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvswdzxcb.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gtgqerfhoa.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxlwcxjz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gthprnbpsq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtstlcqksq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtssymwuds.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtudrjoybj.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gtsygkuxue.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtsvrxanuz.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtlayslxkt.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gtycmbqbhy.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtfkqauzdr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtnotfgzrg.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtfgwstcwq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtdxnanhab.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gtvfywnzwc.html

Py:   def greet(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtbhuwzdxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gthtlmltfp.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvsmcmcpr.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtnosuzpyn.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbtsaywy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtpxxvichu.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtjogsdhab.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqtdbgqn.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtbuigmkxe.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtzbdelqhr.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtensharev.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtqnkctkqj.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtqkxocijh.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtwhyncfuh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gteicbpzni.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gtzvjgyavb.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gtlntjrqtd.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtzqejjttz.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtozjcxkst.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtplwbifjl.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtsuirwvrg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtvnzftogj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtuggvtfno.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtlgklmpin.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gthrufiwoa.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtaqeavdgc.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gtoytraquh.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtssumugjm.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gtrhewjucq.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtlbocgfib.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtbyokcqvm.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtdrbympml.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gtdpzvliri.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtmzkpjixb.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtbfyhcbys.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtkjiraudt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtffknzcfb.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtivaakvan.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtaddnqmix.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtdhkaopak.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtqlddsmfv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtxvmsrihu.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodwqjilo.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbudwsuyk.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtchsozhly.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtchfmgqjt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtxtgtibgb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtjhtstjur.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtxebdcger.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtyrhqhngm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtplymnrbp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtiqdrffaa.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gtojfgvhmi.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtsbdgiucf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtsxotndgl.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gttaapxtqr.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtypttbrxm.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtlwwckmru.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtqoltxvgb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxamlxpu.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtsftwpttd.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtblspeern.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gtsluvrgtt.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtbipobqnb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtscaljemb.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtjcdhznkp.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gteppjbuev.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtksawlyng.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtaluwnntp.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtlaxlfbwd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtxkgmqwti.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtwbqxzsqf.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtqalnwkxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtkgjrauxs.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtjfvnrita.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtoufikcrk.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtlbvhowvy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtwsrewyff.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gtxlbganot.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtacayhvib.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtyxxvbsov.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtmnudhxdx.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtqzfcxxhz.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtfbnllgbj.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtqthmbqxq.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtsuvdfjrl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gtbbzgtqqu.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtoqvkrjvh.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtwcwioqsi.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtrafxjuwe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtjuhxtvay.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtsdjhuygg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtsulqgfjd.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gtziiuetrf.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtzxpenctd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gttpqgjarl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtcgjbutwk.html


<!-- 参考信息 -->