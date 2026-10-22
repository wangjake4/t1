代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gt2erqzxztt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2rvubinax.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gt2wsauzxkr.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gt2argmkwtl.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gt2gdmvkbox.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gt2namraipv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2tqhknkpg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gt2tcztvgqw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gt2nkwfoapq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gt2aowdqqmf.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gt2psluexph.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2vusposcr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gt2efffruyr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2aairbnvn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pihzglvf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2vnkobtny.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhzgfpla.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2eyelibow.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gt2gwvzhrnf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gt2faaukfuh.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gt2lgadbvwg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gt2gvwhzefi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gt2cdzdmfup.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edyaqtsc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2znotluoy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2madouqrs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2eveetowu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gt2ycbbjhxl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2zygodpvf.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gt2wxkjinrm.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gt2rypwcofo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2qcanxjyc.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2alkwbnpx.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2qqgcgxbd.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gt2rdontxut.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gt2gecujzrh.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gt2yzsavfqa.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gt2frdcjtkx.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gt2cojhhsot.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2kilsoffa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gt2ilxengyh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mxemnfop.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2uagwlgii.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ohhpkkeg.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2ecwngese.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2xrkmhtvh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yluakemm.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gt2iaadmkot.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlxxdnik.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2ujajssfm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2tftatgru.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2ajqfntqw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2icrldykz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gt2tsnvbdxr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2vjxycetq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2skyzybau.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gt2uwkasxgg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2oenlkeux.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2ujoneook.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2nbzuytzy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fktrhtaj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2goakvhnn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gt2xnjnhqkf.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2nyjydodj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gt2xpxrgamo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ekiaxtbl.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gt2qtbraqpr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zzjbpdnr.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gt2qzrnikds.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gt2spwcsgqg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2sklivvfe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gt2cjyngcnl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2lbdbouuq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2uenxcnsi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gt2najfgayi.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2vraxpegr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2ujqhdzca.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gt2wuvbqvkf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkayweju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kujydabi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2jmlbouel.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gt2ongntubc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2cpszneqm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gt2roslylbu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2kxhayhpy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gt2khydljzu.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzowlzmi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2xbjrmlcn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kefbizlu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2ndtatxuy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2nweplwvx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2adexadnv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gt2ehjryvob.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gt2wqwmnydm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2woszqroz.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ytdljcgz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gt2fxrtcwjo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gt2cvpzdqkr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gt2lfxjkhzb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2jvkyiwvk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkrtfuzv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2eakifvos.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gt2mvzuzcyg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsqxbxuk.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2eqwnside.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gt2qbcjieqn.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2tzeccnev.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjbmvsef.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2cttwvzqh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2ynejtngs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxeftxbo.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alobrqva.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2uhuvpscu.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2morybyjy.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2vhxkiwps.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2ccfrmdeq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnlsozmt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2cbpiplxy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2idzxlvza.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2mfsaugjr.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2acbelbjw.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2zylzgxdo.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gt2isughixk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2ugcuppfw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2xtxnqvkt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2hcflfzam.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gt2gtlrjmah.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gt2gxirgpiv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2cggvcdjr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2ajrahivx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gt2wgmdkodl.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gt2jglhfoib.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggvhkysr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tdayrhyp.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2xstbaqwn.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2coeckgqv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gt2uoilhked.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gt2lqhpovsk.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2abanlbhp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gt2gbxwjfwe.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gt2pxserdcx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2vndmzuou.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2kcutnsga.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2ktksutqb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2uqtjmjjc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2enmdqlhm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gt2dasmelqo.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2fclnvumz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gt2gvqrwtek.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gt2ktnoojll.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2mwhuyygh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2smpuatgj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ftdnhgab.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2jfltluiv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gt2pfkvumgt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2rpnkyxbv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2jpwwdead.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2irzerdoe.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gt2ehseiube.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2rizhjfep.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2dosjyyeb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2tdajlbvu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2diaazfgo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2wnifqliw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gt2maqxzydx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2llmxycpj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pobkyfga.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gt2zakilyzq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxffmkgj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gt2geitiahz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2fofnmyda.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gt2lrubzkhe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gt2jvpxznjz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhxwodyq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2djutfmch.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gt2tuwczpfv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ajpxgfcw.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gt2wiwbrbvx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2tbagunpw.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gt2xqbduoee.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gt2rzwnkige.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gt2ifsgprch.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2kpegudrr.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gt2oytcwikk.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2vikffago.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gt2yzyxggka.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2dysvzgek.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2gnckeduu.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svyepdbv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gt2nupgypte.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gt2ccnosums.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2zzxjwpse.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2dpydksql.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2eihnbtde.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gt2pxhnvdgu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2ituctcnl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2atmbljxb.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gt2mguxcakg.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2dsrvxdkw.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2voaerfag.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gt2wsnjzemu.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gt2pywdtrqd.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gt2bmuezaiy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2iodufqcr.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gt2tsopqpgo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2ibgcbsqb.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gt2euyvdjsm.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2tshzusnf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2yczpbcye.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2rbnfnmhv.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2obzpclht.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2hnmreplh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2apwxtgfs.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbvcaxtr.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2wpvexmwn.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gt2htrzddtg.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gt2qxdwsnrx.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2ogtmcsjk.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2lejzglmc.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2eagoptxd.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mkskvtxw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gt2fwcfjkvd.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gt2qdyfbjtl.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2eabibhgc.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gt2xbtywksm.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2dxrutner.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2jlfwvnzr.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2amxrtcrl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2ovmmcrne.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2uquxsyqm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gt2zsxqhish.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gt2mukmncae.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gt2bylhkxmq.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gt2widbhjfx.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gt2nsnmirtg.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gt2zfbakntx.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2wosiedcd.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2oxvboups.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ywevpaka.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gt2brnopktb.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gt2bkcdpipa.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gt2tlydrcro.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2sxynjfrd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gt2schytjpn.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2tqayfpow.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2kzgiqffq.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gt2xwnxdegs.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gt2ojhpvmyu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gt2ivddynxa.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gt2lasyocgs.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtuhzyqz.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2udpyfjvg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gt2bwdmifkt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmiuzvfn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvvjdcer.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gt2njrubbzf.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gt2vhqdbraf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gt2cxnidxgp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gt2lzsxzevj.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2xarwjwwv.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gt2ojvkyath.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehlzcsvs.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2wpftryxj.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gt2phcvfasq.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnqliakf.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gt2tuyqlpzk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvgjqoqc.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihjuukgj.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gt2lijtdugw.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gt2wyjwlmvr.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gt2daxecmid.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2mnlnlfqk.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqnasgoj.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2fqkmjuby.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2utdxfjqn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2hghculsp.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gt2tacgdhli.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gt2duiijcml.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ngsujmdy.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvctbnmi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxydcwqg.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2kexnuuuq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edatstrw.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2dywwdbas.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2omsbjfsc.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2dpqckhcl.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2eacsrgel.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmxlmnto.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gt2hlphsndr.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2rpebbdex.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2qrfdfozb.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2snctgcao.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2gwcbitup.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2lqyerdwc.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gt2vvyyjnpp.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gt2fkjeboeo.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2kcyrmkpc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozdvktfz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gt2pmjlxkdv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gt2jdkwpcyz.html


<!-- 参考信息 -->