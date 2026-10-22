代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwhbqgro.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onxluakf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kszkpivh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gt2gqumhivs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gt2soshnmqm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gt2fnfiblgw.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gt2rdxdtguv.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gt2punxeofq.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gt2lpcvxvlj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2qqfmlhsz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjlriawm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gt2txsxmobs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gt2vpesrkix.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gt2ltlatvou.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gt2nknhmptl.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjpbkocb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gt2jvziwehj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvcgcihg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2qkcfwywp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gt2sifazlpf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2wdzjgwdv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2ycefgcso.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gt2hxbqarvy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gt2iiohnuia.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gt2jxmapagq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gt2yjfeaezb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gt2qajropkq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2qfednvgs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2kamgrzpg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdlofnms.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2facciteq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gt2kehdeypv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gt2owqdhtng.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gt2ckknyhrj.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gt2ffeaiepj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmwolmah.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2qxtxivch.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gt2pttilsxz.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2grxpafzw.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2gzlwbgym.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gt2juscwffc.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gt2jranbxoc.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2nwctvuvx.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2jjpcurqm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gt2btxevxpb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gt2meevxqcq.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gt2rkzqvpon.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gt2mdonfnnh.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gt2mygcdjqy.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrthqwsf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gt2pcrdwrpu.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2gchnwmhv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gt2tvtnvpij.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2kjhjrzfi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2atqneiim.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2zucnrrmy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2jkkprnly.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2jdlqksxj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2hxsdfxks.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2xjntpuoa.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gt2cohvanyj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2mmgsywjj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2vtxkstqu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2kxcknskf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2ujjhtmwi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgxzffqd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gt2kcdrdlds.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2enoinjfx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gt2gbfpvvkx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2qtdaxjyb.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhsowxdo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ttgnbgal.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gt2iqecdbma.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gt2uqmsiznx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2ivkgiadz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gt2eooykzch.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2swhsdukv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2gmsjjfzf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gt2ljdgdguc.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2yirhrtkb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2hjhfliit.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gt2qlefmxba.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gt2bgxizjec.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gt2kipnzodk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2zjqmnqsm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2abquxgoe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2azktcopc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2eomehupv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gt2ocqtfpts.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2isardlpn.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gt2saksbydr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gt2jhpyhblg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2sgmstjzt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2ginobxgs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2fijtgkeg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gt2hvufktki.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2jkyuoqwj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2tspizvnf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2ieawezdk.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oftmdzrr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gt2huruvztf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gt2uyfwkzkt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2ryiysmhk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2uziuxcri.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gt2vzsxfyjl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2bnfyeqyi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gt2shmvjtof.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gt2hxavgrlk.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvpulohu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zipidscd.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2asmvlzon.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2cgeuozvt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2lixiswoz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2fogzmiwc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gt2tpcxqpta.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2qaggqqjz.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2cdjddiwd.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2qgptprwu.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2yunzkkwf.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2mtetxmev.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2sovigbkc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2pkepfmso.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2znqhatyy.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2rhnfwhpq.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2xqlarlin.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2qefhekiv.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gt2ksqmrmkq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2apyhzeuo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gt2ctfrajxz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2wdemloiz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2syhljzke.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gt2dndgklxl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gt2tdajyois.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nexsaziu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gt2aiqbzxnb.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwawhzmh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gt2raycmmst.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gt2wyzyygfe.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2vrrnunjb.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2tyailvlr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2gvhebkvp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzrgpngv.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gt2lzryvckk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2kwmlltoc.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2owotionf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2rokookpk.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2muzegasa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gt2ulbtofqi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2sxmoveug.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2bpvzxjtk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqhdytup.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ioevpzya.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gt2vwsdqmbc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gt2zngsallf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2oiayjqgi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2xsbjpira.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2frpoowlu.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2entgakgw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gt2dwsythxr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2wvdygnmn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2woghlbgd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpvzjwod.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gt2fclpaofy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ejyeclpj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gt2vrnaydrs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyizhqea.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2nbbmcjrz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2dgbylkys.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gt2qqtsnoda.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufbhtany.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gt2fjmdghhw.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2jrtvkbjv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2ivknbhne.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gt2lzpyxkfm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2gnpfeuhn.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2qsaimdng.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjbkcbvo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gt2subkjzra.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gt2putxokba.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gt2epgtjnoc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrocxoiq.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2satuzogw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2pcdlvynx.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gt2mrkgjrbs.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gt2tojbyvkc.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2afigwfmu.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2tfemwqui.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ammmcqsb.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2takxreri.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nowvjmyo.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2zczofxta.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eenzygiy.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gt2dbqiwwoh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gt2zjixrgvs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2qjknkbjq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2ebchfbzt.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gt2begurrxu.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2gxpcgwpr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gt2qeddotlt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gt2gbmucvfs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqrmhjvz.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2svapprne.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gt2tjyckxke.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2jctalsfv.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2gvbyqipk.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxreqsmd.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gt2khxdvaee.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gt2ocbvlagg.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gt2ginutqos.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gt2nbbwgdis.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gt2yuwoxlcj.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2fjystjkr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2breehixo.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2frjdghsg.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2djhckzkv.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2owynmwdd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2ncotcgnn.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2dlcaioxy.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pijmlfid.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gt2bcvpryzr.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gt2czflfyey.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2qqpaykmj.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2mhgwdpwo.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2cezeyxsu.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2zfvxzuzv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2kyeujiak.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gt2krciqgwr.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gt2ayinyaar.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwhworam.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gt2szfgdxlx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2yiywqgtp.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2jswmoscy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2udewkiem.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zwwmukax.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gt2zkwackex.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gt2kidppjtk.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gt2jafpnqfo.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gt2tmyyvsyl.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2wbryyofd.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2mdsdxeiu.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2pjotylsp.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2xvghlctx.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gt2ybrkilcz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2snvrfxjh.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gt2vnxcttmy.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gt2mcsuwbkn.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2twnrtjii.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gt2uopeqldd.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gt2nwelnvmd.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gt2bvvlrzif.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gt2vfhxizld.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2bstonkcu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbgxjglc.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2gacbicxp.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dvuxrzbz.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gt2sndlncmq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gt2zatzylpl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gt2jqrgmxel.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gt2jqkmfpxz.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxsjsslo.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gt2hhxxezjn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gt2skdbqdwc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gt2uuowsegf.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gt2oqkpkiip.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gt2uhnxlzxr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gt2nlwfvdme.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpxqxlfx.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdhogxgv.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2bbubkkbk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gt2nefhumfk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gt2idaeizjz.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2zecazdqy.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfuijcmb.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gt2rdapibxc.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2evnsgjos.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2selhbgbv.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2pywbqvjf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2rzccletg.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2mxayyjga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2crchrzlu.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2ykxlbrzh.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gt2liurictk.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2bxzkpiuf.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2zrhdjxtr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwxeamyj.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2lynahfnm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2htzthtmk.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2zubjbkvj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ledlfcuh.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gt2lqoiyoor.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxnzumru.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gt2sdglyqdq.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uplkiotu.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2qkkdhjym.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2ismcwssw.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2qulkjtca.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2ycvcdyam.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gt2kjcgguoi.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gt2xsfoxtyj.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gt2xhymdvgr.html


<!-- 参考信息 -->