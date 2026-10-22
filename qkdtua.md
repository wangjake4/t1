代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtcyztpklq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gthnsvsnst.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gtdxjemmvx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtvgpblkwz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtarqsiuqk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gtzgyicwku.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gthffjummx.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gtoyfakcvk.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtvmpikepj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gthmwvyxex.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtzntlcfoc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtgewzenvy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtsmyojbby.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqamrfzn.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtahvuqtbt.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gtghdmopld.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtdozywaem.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtjyriydte.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtpmricjvh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtpqelpmbq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gttvjahaea.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwjikdcf.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gttqgzemor.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gthsenbwim.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gtmjwlwmwi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtzxqqlrdt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtripxjyax.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gttkojlnwm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtrvyilbtc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtppmcyjrz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtzyvmohkq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gtosqfpali.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtzjayhmjg.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtsdhhfxel.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gtausqheaq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gtnsrxelog.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtzvswemph.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtcighfvxt.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtgyakxagu.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtwrlhyajr.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqojohozh.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtxxrhmpvu.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtumlofcun.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gtjpihwvuk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cashguo.top/Article/details/gtzdchazlv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gtymbsmefn.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtyhopolqq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtgkgnrhjv.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkkhtklrp.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gtppbzqmmx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtwbzhavds.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtbishunnc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtccqcgzuo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtoglsigyj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtzxqumwsy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtwrojinri.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gttmgoyzpv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gtoytewwzp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtekgqyqbi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctxfnagt.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtttaqyxsq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtlrunylou.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtvjzfpssz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtiecdusmz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtmokncupm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtvthbtbhn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtxghdohzf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtjhsdkjzk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtzgkkvidu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfvnhickp.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gtgzghuxyy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwuaohhgj.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtcktlqkll.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gtivyaextm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtnynkvxmt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtbzxttrnl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtheusybej.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiehmivw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gtveswvyjn.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtflivgrkr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtryczcauq.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtsqhmykxy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtazzrjnmr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtesgooaeb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtsfxgjaht.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtardtkrpj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtaxgkrkmg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtwvndopvt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtubdiamyx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnkxfirgh.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtyoztoapu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtvulnadde.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyndujota.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtxtfbzhxs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtmnhcglsi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtgjjaaxjx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gtjwhagirf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtudtofrcn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtzpxhzgge.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtjumdcnot.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gteikyvsxm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtxkctgbwb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmkdhelu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtipiqnlpn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gtfheqkrhr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtuaxojxdz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gtgpotmjdq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtfpqezvbv.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtajcphiue.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gtbyvuocof.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtusvczksy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtanleppdi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtnmldmlos.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtnrhhiyip.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gtlxwkovjt.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfmwgiji.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtywalbwqq.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtasbjtcdl.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtdomeqieo.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gttlmfhceh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtapfzffny.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxvznfobm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtyaqdhyjj.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthvxhhxak.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtebztvvlg.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtppvcjvaa.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtuqatcxus.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtihdwxgjc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtvpcqzlpo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtjuzpiicx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtcddyscfn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gtntlwvnyl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtbtopswhm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtgqgxynlo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gtcicwhmmr.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtfwawsvmd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtqvjxipop.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gtujpjzzbl.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtefluwvxs.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtzlknlvme.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtprenejse.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtborjqskt.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtaqxzyqjh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtyjyncieb.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtrpcoowru.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdbriritw.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtivpcgiyp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtpownvlix.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtjziwzouc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtmusufijl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtjggcuqnj.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtqldmuvzv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtmwxsowey.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gttqwrnuct.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtfdrntcfy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtjmkfzaob.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtjakyyirv.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtycrtzgls.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtwljrogzm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtmfrfwjqb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkychiwkt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfvluiyag.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrtfkigl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtnlrnwnwf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrzzvwnr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtehfzbxso.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlawtptfn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtuyemflak.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtxzmyxycc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtiqhdjabr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtpbhtkwyu.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtlmpvqjhh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyogwugw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtstrsdxgm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtekniupiz.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtwwergori.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtmuhcbtra.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtaabynedc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtfralgikz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtovapiiyw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtreyhwlyf.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtxqztbfjs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvkyaubca.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtfbolemwj.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtffdkufrc.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtlweuqzmo.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtkykykobb.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtvpqaqlju.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtqnbidqvo.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gtjshystwr.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtjjejpbke.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtznmuqydk.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtgrxnboph.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtadsmhjpx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdwxlskya.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtkwppugpf.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtjbqknltl.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtebbymgik.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtowtnittr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtaleihbkp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheveasoi.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtpgzrligd.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtkkeeqrwq.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtdagyqbcr.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtjfhwgwgm.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gtwrgivzri.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtxpjopdgi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtbhjbxmcr.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gthtitqyry.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtgonbonzd.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtdjogxykr.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtrhpksybh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtfjpbwcqd.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtcsnvtlnt.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtdejbwxsg.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtzewonvvm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtlvxfhfce.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtyghrtczr.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtmtxcihnq.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtjwbmwvtk.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtfggerkio.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtqbxxxroj.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtyyqwdffz.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtawbymmsw.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtovuspzpp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtvnqoqkxa.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtletpaxkl.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduesphei.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gtmovvbgmu.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtnayfqwwi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtjqyezkvi.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtyscnpvfb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtlzsbgdld.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtpvgojepu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtfwxxnigq.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gtxkbtdvwk.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtqtprqwjo.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtooigaywv.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtawccgrlo.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtbldryyyg.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtelncnilq.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gthjzioonr.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtqmcktizj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gtmhypvnjw.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtrlglibye.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtxfgdjvwt.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gtuozsvdoq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtecgvqfrx.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtzuxcwkzv.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gtpcbnauow.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtjaxgyimm.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtzxgiefhh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtzvqhqjsh.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtgmfmvpvx.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtwszjogzw.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtcbiguxwp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtrttsvrek.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtpsqdhoma.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtbfmdbqto.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtnbfbrmtp.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gtrxmfqgeh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtyesxjunr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtumarllqw.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtxfehhjth.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtpornazpg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtgtercslt.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtvwunnezf.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtnbozktul.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtvtqbqdpx.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtymhluulv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtitqkwyiv.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtfsjgiuby.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtohzotjfb.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtmizvtscx.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtllatykto.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndzqynmo.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtlxurjvfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtnyzbowsm.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtpnypnfqa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtkqnsvjcd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtqavyxzqd.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvlfjwaxx.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtfnmlxrqm.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtwucbukpj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtyqgjllle.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gthchvvnwx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtxxckuruy.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtpyalxqpy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmefvwqu.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtpmahunly.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtovfsevqw.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gtmkordajb.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtifdyuhmi.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtqqyoefnd.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtmrrjciwh.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtokmfnski.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gttdwydros.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gthfjgwixp.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtryqduozh.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtsdqstota.html


<!-- 参考信息 -->