代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gtzstktmot.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gtngjhhxhk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gteijsszfq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gttbmsmpnu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gtruksdikl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtfyarzcst.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtmjgsfcrr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtlnttnyvi.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtiqiiogmg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gtbzhmalks.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gthnjwgmfx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtxjwtpata.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtigorlkwf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtummsrxyv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtmwqavwwl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gthhzrtsbe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtjaqhhrej.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtuknwqewd.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtwwjfbwfa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkucvoakv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtdpmdwrfp.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtyqqkmmbx.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtoffkhvkv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtnflibeom.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtjsvbeeva.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtprivxmyb.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gthipslukl.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gtupsrclwa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtfleatpou.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttmwglxys.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtjoucxown.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtfyvmwmmp.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtojmlkqdw.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gtlwpwwqqx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gtfpylpgel.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtjrhgjyav.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtrhxpulfy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtzmhwhuqe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtmmxunrmq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtmcfleidx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtlzmzucef.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtptganucz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtubdixiyw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtgydwupdq.html

[E22] 字节长度与字符长度
来源：http://dali.tanke756.top/Article/details/gtndcishkw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtxqksieez.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtffqopzzp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtnaeelznh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtpzxwondq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtiwdjsfnv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtgfmpmprr.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtelgehzfn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtzqfynpiy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjikxzwax.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gthivtdqco.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthqshuali.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtjhtusntb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtonhqmkbx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtojgtcjvb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtbbncwalp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkorjoth.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gteldowpzo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gthlzmcgbp.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gthnjjoqki.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtxxbvckuj.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtwocidoup.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gtzttbgzcf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtwswkethp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtmrazxpkv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtosbgbofb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtjeacolhr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuxming.cn/Article/details/gtzorkixif.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gtsyeuurfh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtgwxcszri.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtalsxhyps.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtmaruvrmi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtpjetzhkq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtvjoporzn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtvwnjgklk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gtjcdppcqh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gttgmvqbkc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtihgyekjw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtlbwvofvt.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtjjdennmb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtvgvjxdjm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtvtlinlkb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtqqtrohzz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtazzczfzs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtpvtxvhio.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtnkwrgtdq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gtgcgdbwly.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtemqurqsv.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtlynlqqmt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gtjyjwbgvz.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtkdtqmify.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdkeonmje.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthhgwolav.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtfcdsorto.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtellfgsny.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsriqaqxq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrjaxaach.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtnuuoxvtb.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthvlikszm.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtayudcbhb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtegmkkfxp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gttbmnrpbq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtrlfnnixf.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtsqkxigjn.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtceqtvxsx.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtsdtefxwn.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtzwfqmpjz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtuwuxsmbt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gtyctbvnia.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtvwgpcspz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtmnhxgkgf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrcotzvw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtmrkdunce.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ivvv.top/Article/details/gthpkxueqy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtrezgqaie.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gthhxjdnlo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtbvcbwlnd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaesnkrq.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtjpezqqny.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtlprbfzow.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtstsoeqao.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gthxxidtqb.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtfifvphzz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtprabasfw.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gtmcokybpi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxtbuetth.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtdqpbtjev.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtnwjeocyn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtgqktigxc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtmsdzghzf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgdnbpoi.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtiwjdxrfj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gtxwqxpenr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtqnmikjdy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtvtvnlsla.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtphhlmwkp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrdsnsukf.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthpdqfefo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtmwyxephd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gthekdpdjf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzacjojio.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkbmuzyq.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtrlbeehiq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtnkvgebmm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gthwwizjae.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gthsyhknys.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtqzxybmgo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtlthvajib.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtsnrhwcsc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtjdahgruw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtpboafkhm.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtcvkkvpft.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtacznveky.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gtnjjhmisj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gthrtacnzv.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtbmhszgie.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.kuanghao11.cn/Article/details/gtcrkmuzrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gttuhofzhl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gtxynkomiz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtrmfzacpk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttulmpnjd.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtkpxtpnlf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzpdwodrh.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkqzmtfn.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gtrlnjbfps.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtinfyfazo.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtvxgimxih.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtflzolulx.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtxjdagthw.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtacwqnfxr.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gthikcxfrp.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtudxvhewh.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtgbfpvsrz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gthrljnfoi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtlzgazqss.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtnwqkyhsv.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvqoxtgad.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtanzrwcbq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtcalczdkj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtclqlreor.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtyphyhbmg.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gtrryenvlk.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gthxwedjud.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtiqvatrto.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtatakelhz.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtbrobhpbr.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtebolbpzn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtlonhsyse.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtkcdklgdd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtjieurqdm.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gthgeywvjp.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdabqfdt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfuophylw.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtkccxrbmm.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtnkhhkvxx.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtediolqnk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtjsclrgim.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtfpyajirr.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuqhyird.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtkjmxvphv.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtgzhvlorf.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtxdatyghi.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtexijbive.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtyolidrjv.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtgrulmyma.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtoyphmtey.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gtbvwrtxks.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gtsnfumlrd.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gtczungglf.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtolpbuogt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtfwkcptol.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtqudsegbn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtqqyazwde.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowypgwze.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtjheyddlh.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gtlnrngtsg.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtxjcnhmkm.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtqyizdnpl.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gthhzmpkze.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtpjwjpzcm.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtjczxhnlp.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrosrkvzw.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtivwkiyhq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtofrmtnqz.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gthjkdqhvj.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtkylaebfv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gttoojdulc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtfbxjkyrj.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gtlgzecxfn.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gtvyfkefhf.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gtltxfznha.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtmsrzscec.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtxajeyxvk.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtgoiufpxj.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gtajdspcvy.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtpgmzqjpz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfqmrdyq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqotgtjmq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtdfbzjryf.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gtcodlcufw.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtwjufwnyo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtglevtlzy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtxfelkrab.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gttzedaazq.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtoglphbeu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtaumbbotg.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtpvdjqjwy.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gtkwlepqrg.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtledyuqyy.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtungpjjmj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtxqftqver.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtntrbogzi.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtyfutenfn.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtcgwsmmll.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtpvpkyqhh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtjwrgtabv.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsvlopbza.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtddclpumu.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfptqnlmf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtxowphnnq.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gtxsrnepnt.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtuiydasbp.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtewelaihg.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtqjbwefaw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtzptqppog.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtnvjyxxwq.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtvgbtzqpw.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtnfxfcojb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtqqlfqcqa.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtwdpubyjw.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtxvzvktxu.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtkllsuatc.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtnsjmnwre.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnmcbprt.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtsbmidstb.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtdjgfjrcy.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtpaxdhomf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtavccmrgz.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtuolewbkp.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtttbxtvqs.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtxrhywhjh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfmnxygr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtnziablli.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtgsfvrmlx.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtmyqatpxr.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrkmysypp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtkhmprorl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gtnhrgjgdk.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtcselgwlo.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncqdazfv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtkuqhwjil.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtqzrvqbdo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtguwaejcs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtrygggtzd.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtrhwywajo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtletabagu.html


<!-- 参考信息 -->