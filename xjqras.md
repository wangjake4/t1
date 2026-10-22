代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtovnfhvom.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtgfelbnsh.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtabavcgor.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtndcrugry.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gttfqmzgzc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gtxfqjbyxj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtzwlctlzb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtkhrmbajw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtzdwybkci.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gtdeukdbmq.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtbjxrxtpx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtvrebrqxt.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtxuzrpezb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gtkdqcuppm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cdnleiting.top/Article/details/gtkwxasmfv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtsmnpkdlv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtoflxzcxv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gttzacnilr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtaccrzuzn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaqamiht.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnimvaokc.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gtkobultiv.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtasyhymfp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawwmgady.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtgkqlwpdz.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtqmqyndfc.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gtmndjoblo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtbvzzudzc.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtxcbqvsqk.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gttmbeykbc.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtpyshgwlf.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gttflgazbt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzspqddu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gtwkrclaxk.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gtbvflssjo.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtfwxfnbcv.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtqdhyrelw.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtcbotjxij.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtwuzxqkua.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtcjzlkzkt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtfwdwncrj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtgkrpyaml.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtowfwntak.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtryxihzgo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtqwsxxjhw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtztlijskl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtphouexty.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtihhpblqj.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtiiloryda.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtldlfavpk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtdyweticc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtsphgbbmk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtbuuulstv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtoscvjhzb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtzxsnfggx.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gtsutjdgxm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljayfadl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkwttycvw.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtywazyird.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjexqnflq.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtrsmtvyel.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtipqzkiwm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkncozxc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtaweyjrrn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtecsmikea.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtdleyywaz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gtruypjvch.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtoyfpmmql.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtylwpllnp.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gthrohlhac.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gtnsghyfjr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtxmnlqgvs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtefzitzfv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtibkxhgmc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtbtgsttam.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gtbyoktuaa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gtywvxgmvb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtvtveekuj.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtutovzlov.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtmzwutzkd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtzhweoilo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtkytcklzs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsuoglac.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gttdtjuljh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtwbysubzw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtcdpvsygg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtjrrfodfe.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gtwewaxnai.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtdikyeeeu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtktuvftfs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtmamjmbdq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtosygcamt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gtobwxruas.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtrlwevqup.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtubsuqwcr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtorgkrerp.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gtoryowezg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gtytogkaie.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtrzsmaxpx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtnnsdfqsy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzvdlemxn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtmqyppoqm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtntxwubvt.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnmjvmdwa.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtqjvorhcu.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtrpspnmwf.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmykwamfs.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtcebsouxl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpkyumfhb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpfzmmyfn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtdgjbfnas.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtscqaokcp.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqygopwdr.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtjyajavua.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtaacdohsv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtcplxqzvz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtfnvuvplc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtdmxzfzwy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtxdavbedr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtsqytphnn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtwlirkzit.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtptpesevs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtlsdafxoa.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtzgqnphqd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtwafrybea.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gtrufhvjxs.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtqaalnpgc.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtyqpityik.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtgvtzrcxb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtvlnhswfn.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtcvmvivrn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gtkvkwpcrs.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgzfbnbs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfenrdwio.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtrrgtdpjn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtwtskjxur.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtewedqgom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gttdnvggmk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtckuiiseq.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtibhrbsdr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtvipnqjjp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gtvfgantkk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtwnxgslrl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtouiyyree.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtuiiltnap.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtkftwffki.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtmrwtagpw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwlfsoqui.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxcibyqvu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gteongdvmg.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtcxfacnkz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtugjcapvv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtvcwxggxi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtsfzndqqs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtlietfjxf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtlslacatg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtgrnfpxwj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzqblkpdw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtsarwqhtk.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtcbkwpetu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkrmyecr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtblrcznyp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtobatuqxq.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtincfnied.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtdwqgqklf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxjdocry.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtxgoeovdy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gthqbtmjjn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtczrhgcyq.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gtufgsctra.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpmscuqte.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtufpjdmcf.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gtkdrktjfd.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtwvapiujf.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcelveva.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtdnoveznc.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gtujbzzbtc.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtykrzzbco.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtkxypkwty.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtpmlzulhd.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtzcunpaex.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtffdelxvl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtacqdilxs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gttfhrcbsg.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthsbhvikz.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtxrcuipvw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtvbafmfjc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtefxsxgnc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcshcuqcp.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtiqpkxecj.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtblgwndsb.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtluhkionm.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtotfifcmz.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtcemcraka.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtpcompuzy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtlbcxwdlo.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwrdpobs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcjiswdb.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtfkiakfpi.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtnfnkvfyd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnploflby.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyhcjghmb.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtbrioiwnr.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtvnhaessi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtwzqnrvuw.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtrgxrnkek.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gthpdkaqch.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtjtutnwdq.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtywconklt.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtuxuzlirm.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtdiydktyj.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtenqkftiv.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtrfdcckaw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtjyzznkof.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtmrdiuqpd.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtbnjqcqns.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtnyneearr.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtlkltlhxk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtshntippk.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtkiutdxsi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtxtfyxvhe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gttfdgstkc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtdzrvejvf.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtqkfjtefe.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkmgcmdj.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtpemjfkma.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtfzjzuuav.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtfzlqsffu.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxiubabw.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtmpcvzehz.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtfqauryrx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtshawqotv.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtqfbaeqpm.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtjwjxdijr.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtoyhntimv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtmkvklrjj.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gtiujjdgog.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtrvlyfhac.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtlevukvua.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtwbewnvjg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtdsqgkjtv.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtivujbsdr.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gtacqpxuxs.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtesyazesg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtxncrmlok.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gtbxhsdays.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtnmgnlpsd.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtobbzthcm.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtecfazpui.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gtoerntlob.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gthctswkhb.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtkuoxkcyb.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtjkihucgn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtytmayvwt.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtkatnseum.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtyfumeemo.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtcoqrpewo.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtnolgxroz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtujizgjbk.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtbltximlq.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtblwgjbhb.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gthddpoqwh.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtdosjkbog.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtntprblon.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtadfcvpwc.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gttjujsvsw.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtplxoesyt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtollctsms.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtgzrgqycd.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtzpszhwlm.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtjnzlxnnq.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gttmjefosc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtkopuswhh.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsimjkfk.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtysiwvicb.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtjaqdvden.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtaqpxylqo.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtjkyojzmv.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtndwetwgs.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtvccysnnq.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtpcqyrhbx.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtdhvpnfkk.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtqffvqiat.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtmmisccfj.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtxnjgoknz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtszdisuvk.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gtteqpdapi.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtgrgkshvx.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtvsbbpxfn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gthikliens.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtodyjctni.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtikzxrreh.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtugtoqocx.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtddxmonau.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtzlihpuol.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzkaszty.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtskyfmyot.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtokwetlpp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gtohmiybzu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gthqujexih.html


<!-- 参考信息 -->