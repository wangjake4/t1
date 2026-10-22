代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2aynmfqpm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gt2dczyixxh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gt2llfkrhfx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gt2lfcmehqy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2zwfuprro.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gt2mvgrhlkp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gt2asywgslw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvwfeizn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gt2qluhsrer.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gt2ihanamqc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gt2nuetlpax.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2mmhthxzg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gt2agboeqcv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gt2wmbkuleu.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gt2dmwifdhr.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gt2xebgtagd.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gt2wiqotumh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2dofcamhf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxefdgpg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gt2brikzgvh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gt2wnzirxsf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gt2ftypnwmp.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gt2zmbnnlkb.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2oklayrht.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iemiehyp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcpkieql.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgrfynj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bscfiiph.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gt2nomxnghy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gt2qacsficp.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gt2lxtysgtp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gt2kiaqhdud.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gt2rsccgpdd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gt2hvgtddos.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gt2dzhiqshc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2olhcybgn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2vypujxfo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2unxfpmda.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2mwnjfial.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gt2avvemfzp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jogsdvij.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2secamxdy.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gt2nfhzyiat.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gt2nrobwhii.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2yjbkxuhr.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2ambskqrg.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2qztdnznq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2lwsunlbh.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gt2dovzrult.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gt2ltrdwjcn.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gt2cwzifsvx.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2kmjxbacs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2tyyebyov.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gt2tbqjhzez.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gt2wrcpckcj.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2jnnmihbf.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gt2bhfslkjh.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gt2kamulkkw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gt2csgldmkv.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jojdppqu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gt2vdyxlniq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqacdosg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2aqtieevw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2eurduwuc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2iordsynt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gt2rjadbgqz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2wcekoawh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrlqqtee.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzxiwpbg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gt2cuchmegr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2aapdcxmt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2nmgiqmue.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2wybluxhv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spguakcd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gt2mtnuiamf.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2fjltbvwl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2roriltjw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2jkariyma.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gt2wewhbkqh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ddugcwra.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gt2csdryckb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gt2crbevolo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2hhiakmhz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gt2ggoghxgo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2rdesmnex.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2aipeisef.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wregdkis.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lrqriqxa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2cinxvlxc.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2mrqpsbiz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gt2mtaixryn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gt2mqkqqxui.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gt2obufmcgi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2bdeksfgw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2pfzpadxb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2qbtlfudp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gt2ncfobqyj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gt2ldzuiijb.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gt2hmsxqvzv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gt2adyumuzf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2xwhfwxai.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2bzdgnpjs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2kpbxhtem.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2skmzlfim.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gt2onfuizee.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2dwuhtler.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2yuphqsal.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gt2pyvjfntr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2dvxcisiw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gt2jooyvtns.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2gbinhvnu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2flqacsqd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gt2lxceljpz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2seuonbgi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gt2edkolgef.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gt2rmoqpzkn.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2meyjoxmf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gt2kmhanpef.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2zfssxzkp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivhfgguq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2uqsuqpiy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2kwygtkqm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gt2trukpole.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ravqvllt.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbgqssoa.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2xnzsxwmt.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2wnctprxy.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2igtoczym.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2exnmqzwk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2phanhrqt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfsobzwj.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dimtwxlk.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ctabydup.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2jqkjzzzb.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gt2jwmonbda.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gt2cxedmdqh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugikrrch.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2zlpfbwns.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2zdbpstgv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gt2qifkjpvl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jylmbtzi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gt2pzevnefa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gt2pskmyuro.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gt2rkcsesen.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gt2pmjygtyu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gt2koqqqurk.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2jkxfwzda.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gt2mvxxrvgq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2ooqqdrpj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2ecynrvxd.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gt2wjartwnf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2smdzacnf.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2tbanoqpc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cicuomsx.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2nbponope.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2xovxcgtd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2xkooatal.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2usxpghof.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gt2ogegtihj.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ikjqgwbr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2wrnigxpk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2jvwetqbh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2boimvlje.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gt2jhtmzcvb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2kvccjwpu.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2isspygzi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gt2fvhvjdyn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2scppcjap.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2cvxpkdpj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ytathtcb.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2lysbfusn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2odafujia.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2xcafcbgk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2pkngwhbj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2nqraaenn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2lcovryju.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2rgilpxrp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2cdhmqbfr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gt2xctxzhow.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gt2zjnlfvsy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gt2ejhrnjlt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gt2ozdtlvwk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gt2enhvexbv.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gt2wiuhzdpx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gt2sshbhzrt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gt2xowtvzpd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gt2xnjvnaod.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gt2eqigyduy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjnjtadz.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gt2totvlwrw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2yfxpngdw.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwkgzolt.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gt2dbkvqwpa.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gt2mhecklwe.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gt2dwqnmchb.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gt2uqitsosi.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gt2kbhlwwje.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gt2xyjxsimz.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gt2kqznwksq.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2qaiukxwx.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2jaclgabd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gt2qtohwcwz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gt2usmqxerf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2imkgloaj.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2htinczbj.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2qxeozolz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gt2hrcbfqdf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gt2eyifojoi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2huosubje.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gt2nwnonctv.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2templcas.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2bpgnnpnx.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2lewfeamx.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2vkkqokfg.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gt2pwcioofd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gt2vwaldbpe.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2kaylvhma.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jefgokbh.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2zuszlcgb.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2chmamtak.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2kfdeeaab.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2utkvgdtq.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxzlqcwx.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2qenhlggl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2gdjnpfca.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2evcntgch.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2vfrthrxm.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gt2lgnhqbem.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2fhcgtrwm.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2plskqvjn.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2yeuuanjw.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2ytapejvu.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2gkbbzvdm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gt2tblqfeyy.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2jplzpexr.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gt2ybxejaiu.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gt2oaypvytx.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gt2tmdhafxl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmtyjdej.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mgxxezbe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2jnnlvamu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2qnrpfrzg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gt2ykohtimq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkeibmh.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gt2qelovqxe.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gt2ypjoihqj.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gt2adtaamoa.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tekdxjzm.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2dpeuqkyk.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2mrchbgss.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2pvaubfgs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gt2ipjaqxuv.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gt2kqqtjkaa.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gt2wcmqeahz.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gt2lkignsmz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gt2iolhbmlb.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gt2btagnwtd.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucxfqxxd.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pztzfrpa.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2akoogtjp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gt2cjwygxzj.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsmiqcrt.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2ctthwnsj.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gt2vikfrlyc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvdiehvp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gt2rerosfkg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gt2qqtaigaz.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gt2iudobsfk.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gt2zirvjvgn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gt2lsnnwotj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gt2lvhbundn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2gzwyqxpn.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caweimzo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gt2xzprrmxi.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2izfwavle.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gt2chboyxms.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvuyyvhb.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uaalirmz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gt2nyqbomka.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2wwbxbysx.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gt2bhpeiiqy.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gt2qibbqtle.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2wdtqpnzf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2jgtpywrg.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2oejscazj.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwwpnnzx.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2wlozzyvf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2fcoejezr.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvnmhcvr.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gokpacuy.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2uuzgmoif.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2ssltkaqz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2ydvgooup.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2pqvdoulc.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zhlkcphx.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2fsuezcqg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2uwcdzfif.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ypicjnos.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2yrvuampq.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gt2reompkor.html


<!-- 参考信息 -->