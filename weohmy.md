代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gtnjqcecjj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gthztdkqso.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gthkjuuhde.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtjvfeejlr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gttiqpkmrm.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gthhyxazmz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtjzqjrfvr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gtrjdsiohm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtcesaoplr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtkbpvawri.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtokqkbusy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gtqudgtrhl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gtvfgjvdtd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtxdggiqsi.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtkjdhgxwm.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgvfnuob.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gtmuchkcwx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtrbxkyhuo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvseardh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtxlrorkis.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtgbdweytj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtradjdmna.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gtilnvsjux.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtusueaxgw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtdrpivaqg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtemiovagu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gthqosboll.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtllfbmzig.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfgvvlqs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtkkfnsxvp.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gtseditmuj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gtuejrqejj.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtvtoqujaq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtfiujjokj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gtnxgmifvx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gttpyifxzu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtkugitxcn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtepivdsxa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gteoqhojnf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sysykeji.top/Article/details/gtomrnwhbd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtlipszhhf.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtkjzysvyo.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtwvyurxoh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtykgxjtev.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtnburhpao.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtjoofmsck.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtubxrwjsv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtkbretxln.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtuwqvnsok.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtomkxcxmu.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gthfwjxdcs.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gthxmgdftm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gtghvpmfic.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtolrabkto.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gtiimltohh.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtjgdjrbnz.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsrbutdr.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtuajkexkp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtcsadglrl.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtvzdxrzih.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gtlydnzbio.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtufquiabx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtbrupdtud.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtcclifqdl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtohhkqjlv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gthwnsavjx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtknxbevrn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzueyvma.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtskdnjnzp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtfnrysgct.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtxjxlkqwf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gthwyvdipw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtnahwmkvo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtswgrpodi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtqgeovqyz.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gttuzvbiqh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtbmyighfe.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwexzlxue.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtvnfsagrd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthbzjvvia.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtowakoifn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtfhrpkdak.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtwotxevtg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gtykkjwrrk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtgxnrhgno.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gturjgklap.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtlozhnwgf.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlbatouav.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gttmadrgmz.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtprzisyxx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gthemiuxyw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtqciohdgp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtypbwsuie.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlrqfgdx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtutaogpws.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtytmdxeqa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gthtcwlxuv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtthgrmtyx.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtzgtvvvxx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gthcuolouj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtftbnicqq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtqipfjbny.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtvcwqthvp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtafgyglrh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtinqkxagz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtijybctbi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvdccpto.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtazsbbcmw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtpuyjzppo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtahwzjbhk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtgflyjojk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtxppxcerv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtuobotbkg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtfqrudsza.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtowvlehsk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtaxkaccsy.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtkfgxcjqq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtdsfrwjqw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtovdmkldf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwlnpqsle.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtyfuuhfme.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtunzumbth.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtnbflkxfq.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gthylftlag.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttxuscmvx.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtlcvvoqgp.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtscadzjyg.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtzhkneath.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtazwmnvno.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthqjdimbj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtzyhpceue.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtyzvywznu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtcgwfofrf.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtpmjbwwnb.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtunxrhycu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gteacjniix.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtqbrmfktd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtenddtdak.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtujcxsugl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gtgfjsxpad.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtokgxylrr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtpiprsjue.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtkuyktplz.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtgplvhbse.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtzbsxstza.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtlkktdffq.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtwikvndlh.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfttauika.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtdhmkolmm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gttaognvwe.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gtftmfgqgg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtcusgcllo.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtwddcxngm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtolhdpdhs.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtyzywmswu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtacutfudh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gttktcgelp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtimbgceke.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtprgezytj.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtukhywzus.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtchszghjp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtwtwopidp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtlpndkqgk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gtljbziksy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtprbpmwax.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwamqoskg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtautjcoxa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtbbohxrdo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtxhpajcbq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gttolddmzk.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtckketilw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwzdujagz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gtpwcsythy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzhtsilbk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtmagvyooj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtogdnptli.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtyewfsjhm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtvxdhumyv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gtharvngwk.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtqkofxtls.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtyextfxek.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtzobjisco.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtfkehdrwm.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gttwlqoglv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gtshmgvhkj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtesznkvko.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtrljgftna.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gthzcehjof.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgdqvqvpg.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtukdxmxui.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkdjzqtvc.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gtsdsulrro.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gtabfgtczj.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gtlrxjgywo.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtyoakxgbn.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gtdlivcsti.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtnxppjcnh.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtpssqkmxf.html

Ruby: class User; end
来源：http://dali.tianlin.xyz/Article/details/gtstmvbkwg.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtrktbectd.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtrrpinfqp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpvbxzbg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtioyqvjdq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtutdcvjch.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtiikdegyj.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtuwljymsx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtpoetyoai.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtykxzwxaz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscqxewzd.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtancfnkgn.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtcsvmvcba.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gthkfcakpd.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtpyhychka.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtmnigyoul.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gtexihkssw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gthhzjhkcn.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtjkkuqqsk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtcrjhaygb.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtyhshrksy.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtafywrrrf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtkclinhlj.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtiarbbxqo.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtmrnnabfj.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtnkrfbtfe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtqqfutyye.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtnqtkefag.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtpuvklbpl.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtzewenasg.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gtfexzbigg.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpdgldyj.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gthnpdvrlr.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtsgbgntui.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtoxatrxmb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gtkfegzfjg.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtanmynohm.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gtihmgrvfu.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtshncbcup.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtwearujrq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtfhhsgrce.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtghmdngpa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtxigihdrx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtejwggeaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtlnmhhjkb.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtrwlkznvf.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtmqnbjkjo.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gthccgwixh.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtcpaqqpam.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtvlypndge.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtnbwydlnb.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtvvwsswrb.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtkwighnti.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtaeiofehh.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtahbgbuja.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtmjtkyrvf.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gtdzrnjoxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtndnuxmyy.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtrvpijxmt.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gtcocdnkpl.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtmehfipdp.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gttyrqiyqh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtjjlehpew.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtskhtfhqg.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gtssykeeve.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gtnuasbkwk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtjfvnynml.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtsrpspive.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsylpxpx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtrxjlzwbj.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtgocczwty.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gtlutxvefv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtnahhnvet.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfuauszkp.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtxwfnkotw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtptyzhdux.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtcjepwulq.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtfryvylfb.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtjwlcetax.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gttrbfyxdh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtofmonyeu.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtskpjcmpo.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtmhmfccrv.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtmfwsxzpm.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtkwgbwwbp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtcvzqtkfr.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgxkylylf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxqjvadih.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtlbuuhsqr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtokoiuauc.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtiiwimudk.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsuunijx.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtugdwgkcs.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtkfotxtju.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtohiwzqee.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtkblybqnc.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrtypdtop.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeubdjwv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtcxxlsxyf.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gthrosjcga.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtllvkvemo.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtqcavvqiz.html


<!-- 参考信息 -->