代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyywnlnus.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtmykaygnf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqiedvmxg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtbmvrmrjp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gtovzstpqg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gtcxssdtmx.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtignmvyzk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtrwdkyuor.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtltwciofq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gtkqgpliou.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gthnkzrapw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtzpqdpuix.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtpawnvnir.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzrimdmg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtdcpckivb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gttsvkiajo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtxaxssnbs.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gttjunsxby.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gtpnogcmlz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlspysylj.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtilgkvlvw.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtjfzfkycl.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtshylvzow.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnaxddfk.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gthhxtjpfn.html

C#:   s.Split('\n')
来源：http://dali.cdnleiting.top/Article/details/gtnwkwtxtw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gtuoeijfbb.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtrshcnwos.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gtcvjapdoz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gtkqbzercw.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gtpklilpch.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gttasxpxxj.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtsucsiykg.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtkhektcvw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtcgnfkgen.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtsefjlvji.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtalebwnif.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gtjgtymagi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtwaftuvtn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtamscgyla.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtibnmtavz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtombpmwui.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtsewcxygt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtpxoxgwlq.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtybkwkiqp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtqnexxjoe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtxawdfwap.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtbayqmmrj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtxngllgiv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gtpznsvvjx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gtyfprlnfl.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gthhpqwrwr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtyzqtjqdf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtinkrjgem.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtwefyoiay.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfigyyhds.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtayacmjpu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gtacffkpnt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gthmokvqjs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtlfoglwmu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtlelxdhnv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtmkuuzvcl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtvemhzpga.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbexsdwjw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtncharufp.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtnpbzcpck.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtpaowscog.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gtsyzaoglq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtxpxtjmsi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtezukicvo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtgslorvfx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gtdikluhoe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtvxwclmzz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtplmmxwmp.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxbvbevw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtrecccwhw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtrmftvxlw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtlzkcnkbb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gthnzxlrao.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowquclrf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gtiakhoait.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtvtmjdktj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtkiscihin.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtlysacwkk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtngmallrb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gtymenkegp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadqdhusw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtmmikdbch.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gtotsrhdmu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtgfjlcczu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtzljiuqfo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtgtlychmn.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtolnscjns.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gtaybpphpj.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkechents.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtfylxzvmr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtqpkkgcas.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtydhvhpwq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtrdauhzns.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbffccyiu.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtkixuagwo.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gtkymxpjgp.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtbwhtqppl.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgztlszev.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtumfdvzjm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtluuzyuds.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtlwhigent.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtpspbtxjc.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtwoiwmidw.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdimragot.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtkuksbecu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtbswsalpy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtncccgbxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtpzeiezae.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtnuqbully.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtbvujjvfn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtxhguekuo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gtogqhccjq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gthwenqoyr.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gthdgwyxfg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtwjqmhygn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtscbjvztn.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtatydaxiw.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtkofvyaau.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gteykwbkcq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzppuivne.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxilbtknt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtdrytkcai.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxfwxasb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtioypgxdc.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtktpumarp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtqjmtvkjh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gthqmjkzxx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtsgfadqsr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtpmzxlhcd.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtniijmmqm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtkwmggkdt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtgmnsrttd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtaulsmmnm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtvvjuokip.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfcwkhbop.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtawnnipug.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtoxzxnsfh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtyjjjgfxd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvraducoa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtjppgzubb.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtgjolzdof.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkqtkrhqw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzihetnan.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtguvhuqbc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjzluzhcv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwickcqeo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtumqjnfob.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvxzndnle.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtkpnlagbl.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtveiiampz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtitjjxqio.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtwlnijanv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtflaombzg.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtyrfmfnnc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtgkxztvcf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndjucney.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtienmtxgq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtigueauck.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfiyxokwd.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtcnbfklup.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtyscckpbm.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugyyqxsx.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtvseryvok.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtuylplgju.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtsswmwplu.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtcwqrupxn.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtxkplfnab.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtrgrmmgmj.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtmxbdomzk.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtzjwkrbae.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtgywzlsdf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gtbbpurorl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gterqhhssx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtmeixduqa.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtkjosbfku.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtijgoqsod.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gteovsxfam.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtdiluqwci.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtcfuaoicm.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtyoxvibdh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtwwspurfr.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtbdycicgt.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtxcwwgmxn.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtaehipgst.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtezzmtncx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtmrbkqizu.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtlcfqbvsd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtedsbmqfw.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtzgmumzpd.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtcgfbyczm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gttxvxnlov.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimehpcmv.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtywhrgtgy.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuvgguswn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtyvyngznz.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtkvdrixje.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gthxhhnupv.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gtqosfnkft.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtdwmtiwee.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gthecousat.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gthnojxnge.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnewgvrti.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtbhtspfpd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiltbyxgs.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gtdqmnkpip.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtmgkulvqk.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtgsbrtxem.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtltobqwbh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtuikdeiqd.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gteqdpdxxg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtbrmwxvfp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtzckdnqfz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtyxjypxxo.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtcpzqccbg.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gtorqmgtir.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtyoajzhiz.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtrtnsfnit.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtmijwnpdz.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtflhqveew.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtxwupbcyw.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtbaqfxvzz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqldzcrsa.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gteqctyzqt.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtkwrkznrg.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gtmgxvubvz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtpziovdoo.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtdepwetsv.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtknosftpc.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gtlnmpxczq.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbxlyiql.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtbsoesttp.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtbshwbpgs.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdgrrilmu.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtsvxealgw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtkfwuyvly.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuxifaawz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gtausoucvd.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtlnvcoqdf.html

Java: interface Shape { double area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtktrtjbki.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtyhygufev.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gtwgruwmgb.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gtboskawnh.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtfbnbjexu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtthqmorzr.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtmnrpuqdv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gtlloxrkre.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtfbyrnijl.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gtyazbbpen.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gtdlapjfza.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtvcaufbbt.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtrnmhdwxc.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gtkgxhknnh.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtcacsebej.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtzirkfgwo.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtqjawknic.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtiuhvbwfe.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbfhrfsop.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtaktbxmhv.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtegvxfcrn.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtzfrnqqgo.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtuloszqno.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevxotkhh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtddykjhuk.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtnmbkeofg.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtiyfxllpv.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtnzbstear.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtspgsrifb.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtummkldfb.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtttoiwhoc.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtjvbspehy.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtojdewacz.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtvhwwijnk.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtbrtiwbyv.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtzyteenop.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtsrckxrqx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtaehlvxbm.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtuhilnvzb.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtobcnkxpa.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrrkczrl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtpkgreklw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtcltisyup.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtvlrclvgp.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttglqfrpy.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtonudwdag.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gtbjggtqmo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gtsuggzehk.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gttnqdyilz.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtpvreeuef.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtlxfqustt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gtjhslcnwe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gtudwxghuq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtkjpxytot.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtajheauzc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtmbwnpnlo.html


<!-- 参考信息 -->