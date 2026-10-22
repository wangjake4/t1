代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gturzhuhkl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gtqmllyhzw.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtgnbphwdo.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtqagxndhw.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtcoicdkbs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtcebcxrwu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtrmoxdukd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtcbgymerh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gtltvnfaum.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtmchtpfac.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gtswwyycsj.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtcmdrsrxo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtndbmrtku.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtmronbeco.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoucwpihg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtuagvxfbi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gtxzicqhog.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gtbabpiuhm.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtgvtkuaut.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtpqhkzvop.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gtupyweagf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtrcaytuvh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtvmfarkng.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtnijawfra.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtbjdtpqhw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtjwaroouj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gthqypqmlf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtsrpaotmk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtvycpagep.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtvffzumkj.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtclaollfj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtgfhtagea.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtsysltjoc.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtwmwjeckk.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtlhngompn.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtorugolxr.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtuoghhmoc.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtoaqdrtbo.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtwxznjmpl.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtoovwdykr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrosegur.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtepsojkjk.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtfmmzwiga.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtkfempcto.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtumrayxni.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtrzfxrhck.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gthhjslsje.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gthzmhljef.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtmkglnrdb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtjowbtldz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtzaqqzmpu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtjwselazd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtdwpnusxf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtzwczvibq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtbavynshd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtkkqaojbp.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtyubjaocx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gtrxybnagd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtigjowqcn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtgcgalnle.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtltxlvjtp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtutfssixe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtozmswgks.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtksycswzw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtvrivuktc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbwbmctei.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtwkqyrbgb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthpptrgas.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtzglaqinw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtiocoxphk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtumsxbmnv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtolzmvuvn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtdrsoorau.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtkvhxemzp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gthatupzyv.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbxvpbbqw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtspgxxuva.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gtyywpexaq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gttwdsskhr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gtzlokeqfz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtsalkojro.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtuzbnnzoq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtbanxrsns.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtsyzjsawc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtvkhfjiak.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gttudscveg.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtqgbcbyfm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtnpkaxwet.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtocsssgji.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gthduqyzrd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtmldmzkgm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtubpeujtj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtbjynttgz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtohhvjgyy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtgmhpuilo.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gteumfqeex.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjwbixzs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtdmcivngp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtahiyxrhb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtxqzmfkfy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtsmsjektd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtackzljdg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gtcoikjhix.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtvpifjctl.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtpezniufz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gtrltixlag.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtldzxfusj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzcvgvjz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtqopostrx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtpddwwcsh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtgivslast.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtlpvjgujy.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtskabzxfp.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtjjjkdgzu.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjsxmjufl.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtsopcunsg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmteksvdy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjjqxesjg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtgcmrfbvt.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpsixwbkp.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtsyxxsozt.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtzvguqngs.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtgnzhqjdw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtaxouzhcx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gtfdntmmoc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gthdvnnfxi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtwppxffuo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtzprnggdy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtrgkhalnk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gtbecqvbyf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtmxlhfscb.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtwbrgqgkr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtgculhhga.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetjoruui.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtphoeqvnu.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtmxbchiii.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtsultmbkv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gtcjjrdsxs.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtpfujcrpc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gthwqlhizr.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtyfziiwch.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthtoqftfd.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtcxhpveul.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtizhbvggo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtvpdwrwga.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtinfagwke.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtpptyaxgk.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwcqoqlhy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtegcufhjx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtubazcezq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gthcwokart.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtaajyzccx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtgeutxvsn.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gteasbermf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtetbbaqsj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqqlnzqtv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtvtsobwer.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtnkijphco.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtumbajzpd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdyucpty.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtiadbssfk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtmrshvqwq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtdqmeatkk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtimzhoygh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgrlshyr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtomjlxalc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gthzuvdcqe.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtzrziehzr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtuygsjymi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtgxsrhnuk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtbihcdigw.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtcxbmoagj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gtpcplrwtk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gteteidzdq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gtchupzltz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtaitesykr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdgjxikvz.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtvtpgvhdf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtmlwdgjrf.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtmikwemvt.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gtwirixcnb.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtjvdvopwh.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzubztvkv.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtlhpwwyyt.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtogjjbjgz.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtxgvvaxzn.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtdycmwxkd.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtjdmxrvkm.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtgemqsktf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gthndrdspr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtvnsqmtqh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtjcujvqef.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklgfqngz.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtmkrdqmci.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtgfuxoxua.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtixsfnabv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtsaargemn.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtcbxhdryi.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtyisrwmry.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtfnmtvdrq.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtwtzmussj.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gtkikugnfm.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtwcgmjrpl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtqgkeoavl.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtsguzwrow.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtffzqavgw.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtbnquxzuc.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtxltomxzk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdtmawvac.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtxqeufjly.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtpkfvigfk.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtxohzuncq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtnfuwfnox.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguquekzc.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gthqreyazj.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtxgajmfdd.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyjerwmg.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtvlbjzzxs.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaakweqaf.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfmjotnwr.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtclylktda.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtzfptevtg.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtshohanbd.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gttmfrueuc.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtwvnnuzjp.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtpycuuiwb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtchnfejth.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtznauynry.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtkskqshru.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtrmxrfdci.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gtuljbmjfg.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtpsatwpsy.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gttglugmfr.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtwduygsrj.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtaetszlwc.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gttqptqvyd.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtsbrcizhn.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtpzxyvsba.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtppnsgfnj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gttipcfdvf.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtjafetcwt.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrusznyoy.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtrtsdkeun.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtheubbkys.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtobccsgbn.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtisbcoeva.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtjdbrucop.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtedkkutsi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtxkfvwdej.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtstgoaakp.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtbzummgfi.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvasewszq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gthgthjrfx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gteyllbjxv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gttdxmeura.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gtezheaaqm.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gtidkmbkoa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtuneczohu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtazoulqdr.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoikywvs.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gtvhslxlep.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtcxpmbmme.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtxodeejuo.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gteyhohyvr.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtnpbzoeyq.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtahqcwyzl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtuzhhwdav.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtfeovhbff.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gtljlopvzz.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gtnchrcina.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtalpdtofu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtznwdtjca.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdgawevxl.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtddlkwuxf.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtqgmpweaj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtujvqdsxj.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtqqoziqgm.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtypnacxxd.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtigefkwee.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtwewxosyq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtfxvzewrn.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtyosjcdpb.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtkfnijtni.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbvoyjrg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtkywpxryp.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtaqckxvpb.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtkdbeukvv.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gttlvsiexs.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtzzjeaief.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtrfatamkw.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtqcsaybzu.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtorwnrics.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gthqravshi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqawzbsh.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtyxeoybhg.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtdmqnqwzp.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtovvenoho.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtreyczusj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtmzzsqgde.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtkvyjdrid.html


<!-- 参考信息 -->