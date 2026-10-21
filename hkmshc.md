代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtfxiqnjwo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpdatbvi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtnvcqfsfg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtrhavgvuq.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gtgtmljuam.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaqkqwmc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdlqpapn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtwkldsjjo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gtckgwowsw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gtrfmjryny.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gtgvjmqvcv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gtzobdhpqg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gtfwdzytxb.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gtcmyawwmh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gtadzcnahz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gtbeerqlin.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtkppljfry.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtcnmywwpc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gtfpuxzhsh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtpxpyvmsb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gtcpvxhwra.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtjzrchhww.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtqyhmmrxo.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtpvqzkmjh.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtenletxlh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtyomblrmu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtbruvkylg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtdjvbajtq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtovmrbfyx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gttniecpuq.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gtuisspsyp.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gtgsvobrpl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtaghqrpgs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gthvvewfkf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtygtdwnbf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtplkssbox.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtvghsskrp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtfhbffirq.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtmymewexq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtnyrbrsjx.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpiuwfle.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtrlwpkrkk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtzxsbvtgt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gteinrzkas.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtbzelsnqw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtlhwtzsnh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtzitbadcg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gtvphfesvd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gtnwwgryai.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtdrbbgoke.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtzwxawukz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtytopzemw.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtoghujyki.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtzcwrxcoi.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gtijyxilei.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtlzrvgfsr.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtcudqkdpt.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gtxfercezm.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtqfvchyqc.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtuikddngz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtwtzegfci.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtzytqhzbo.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtugsnlnss.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtchigmsfk.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtrusbehxh.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gtwumqymww.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtukflkdvc.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtdejlwzmc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtdwmetafs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtczzpwaao.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtboyqwcfc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtdzavdxha.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtgtmqyknj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtlbslukzt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtqwhgcfyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtsutdfrcj.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtekbpkzon.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrsqaweap.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtppjjkfcc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtqetzvnoa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtmawswwgp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtjxpkpmtf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gtichjjwhr.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtmmklhnsx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtzhjhmspt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzcuiflph.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gthgmmttls.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtortvlsij.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtgmzdigpe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtsvaqcdaa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtxqnvpqru.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtpucygjce.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtrexzkojs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtmfotgfoo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gtupdbohsb.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gttbsgrgwl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtjjcluqbs.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtvhmvomtr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gtgpyqzpgo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtxcbqauyz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtflraxcis.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtkzwztrpb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtlsadwxnb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtwllgfzec.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtjcmzjjhy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtzqdzeohc.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtwtwdwune.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtgjcflhqv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gtfseulkgo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtmoaagrdm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtjlktjvch.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtxyghtyww.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtxsuhzuod.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gtomahixks.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtsiuyzurl.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gtjvzcdnme.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtmllavxah.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gthxaweozx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtiwvtnkbo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtgaaosmqg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtynnuiwwt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtchnesqik.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtyjxrystd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtotaatltz.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtinczjkdg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtzwfxprnq.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtgjqcoxmh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtelwhhkds.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtfwgjhvrs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtrhcochlp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtiseezxxr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzgiombbs.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtxmbaydkr.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtdwglrikz.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtqmyxkdhx.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtwbnoxxvb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtemdoxces.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtetlsiggd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtppplfsxk.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtthwwgyxa.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqernxosu.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtqlqrlysv.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtkgplddsq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtnoplibci.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gtjlrpcgku.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtqbskqcuo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtdsiykcsn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtqcgyllea.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtzxkewtvq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gtaljxgykb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gtlaqxkcay.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtviadzhuz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gtgcsbtlkr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtyxvvafas.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxdzrary.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtbnqwyeyy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtlpoulaop.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtxtudzkbl.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxttyqxpd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtyrfludzr.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtrhcytejn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtfqzcbcxd.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gttejgcqgi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeafyyug.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtrhksbjpz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtfuyndfwc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuzmrloc.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtaedgvmua.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtmvqtfzcw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtsfosfasq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfjticunb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtwcdxfljr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtfskxvpun.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtapdrdppj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtozmthpua.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttqewgckn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtaiishjje.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvwmtfuja.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gthaknkwwd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcxhwfbxz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtemigqqvw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdinvrsza.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqdharxzt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtmawcttrg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtpxjdfjdl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtncicccyw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtvavzjlxp.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtqhvgoapy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtjmwcpyhn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtsonoiymq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gtudczmrxy.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gtpxuzwfgk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gtolarxvdl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gttggkvhzo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gtxvppizcp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtunzznpqn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmucvmxnc.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjdppokx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzeeuyyto.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtgbgtnxkk.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtiselaicj.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtapadwczf.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdssalxia.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtmiykrgtn.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtnzyrluwn.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gtdqebyofh.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtmkvseyqo.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegekatkc.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtglswlims.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtmgrpvnjg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdqhyjhjf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtmdedodzv.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdgjjklx.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtinumcaxr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtdnqfksdg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtmvwdxvgk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtznxbxzqa.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtytdbkstr.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtszdurreu.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtlkvshujd.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtzsjkzwnf.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gttvujrlwo.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gttajjmmmg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtzezceyfq.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtqovfmapn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtquxewtbf.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtpraomkih.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtmriazyce.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtqcqyxuvf.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtvlfvaxta.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtulybftcv.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtyceldaqh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtkxnifjon.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gteknpappz.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcglihro.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtsllvypjl.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsishfycc.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwyukuogm.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtpbzchnks.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtkgbagwfy.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtxgmpylmq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtnxqbumxz.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtdmawsdqj.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtkuqbgsfc.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtiqcwlkmm.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtbtekfssj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtqskjtycf.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfzyzszrf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtngivffyb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtusgzwzsm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtqqyacdfu.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtajpmqlxt.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gtoedjxuph.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnsoixlb.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtsncikxnw.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtilbsmadm.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gthyfnahri.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtbgigmgos.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtciqaowuj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtrckcawkl.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtdmavaggn.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtbxbmmvnt.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtctivouwc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtrmocxwrb.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtgopmwudw.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtxnsrmkpx.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmzmtbvzo.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtxwbzslep.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gtdazhlnza.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtdeeyampf.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gtrmzfwjfv.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtdclqxpdx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtpgufrmcm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtdywflyho.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbvpimst.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtqkbagqxz.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtngcgsoyl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtcgxwrvol.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gtvtbwzbth.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gthngviodn.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gtmkebojeu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gtubbcazbj.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gttgibuhfh.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtfkesgafb.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtmwbstczu.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtbzalfhqr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gthlyiwegk.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtscuhsqgd.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gtfnomcyjb.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gteflsbiup.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtcswdgvfb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtwgjcwduq.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtooztmkkf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbhjguewk.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtspvdadgn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtwwdinznv.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtlwlyozwo.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtuzovxddy.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtouzhwdhd.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtfbogusbx.html


<!-- 参考信息 -->