代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gtartlouyr.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtrhtmeamc.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtcgoycltx.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtpmgvdrci.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtocxpyceq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gtgbsbnubq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtwtyqbwgc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtdibdzkei.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtztjzcavp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gteiiizkby.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtsvkxcldp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtkroaczfj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtzclmvmmq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtsrthqwpt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtaoxachzn.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtturharvh.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtdlyaljyb.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtqlqcrzpf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtoyzvpbde.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtxbbvpdap.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtcwpdtrez.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtmsnnqkuc.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtiabrykar.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtrrwbvkgi.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtrcauqmrs.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtrwlyxmca.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtnabsbhns.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtclhecwmi.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtaoiqkkyt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtgcmtopad.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gttbfethwn.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtupxblehr.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtmwuikvzh.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtxgolzehx.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtxptymqho.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gthaorlmnz.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gtalqujkzg.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtrhqqffdc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtvdvjkvze.html

[E13] 逐字符遍历
来源：http://dali.mhx1999.top/Article/details/gtzyddztul.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gtygbgxqzz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtgkkdusjo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtbgvgdmlm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsmfxxtqk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtghrvmqsg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gtjsdmgohe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gtvgzanuwp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtpacwwcrd.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtsjykiggy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gtmuzviagc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gtjzxlgpvf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbkykupj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtcymflhde.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gtxsjhgszg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gtegosmbka.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtxkhnasdr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtdkaaoqgl.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtbrjotexw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtwbdgohqm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtgnpwwtdq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtpchjrmau.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gtgckqbdwn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gtuxuogjkm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbkqbvldb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gtzpltugav.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiqxaqfq.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtwwmnkffj.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gtortxxeec.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtwnswqpis.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuafabclx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtbntgsrxa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gtlnaccgbl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gtphgfkguk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gtisjmzkzj.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gtehgctbru.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtaqkpwpfd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtesxtuftn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvaerqnf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtqrkjaxpj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtbiynazeo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtaauqzxcv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtrbounoks.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtiomgmhwt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtfdjpqdlm.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtsszmvkgd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtfyrimxzy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gtyxmitzvl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtfvfobpoq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtpveqajta.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtzobdvnfo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtcnvwsarn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtgszparqb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtnqkryfud.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gttjlbrogt.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtgxppxlzo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtjvyjfxst.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtkznsisnz.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtzabnhwbx.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gtooblvact.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gtewtctcij.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtkixuptte.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdczdhspe.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtmefwglix.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtdpljytzc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtwhsetimr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gttssxdirs.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtldljkspt.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtukexbqkn.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gtegthmrko.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtrvbtazyj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gtbjsztyio.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gttmptvuid.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtavuwtxur.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtcbdmtvli.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gteqjulzeu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelbdpote.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtvscytkfn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckdvazdu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtveihjpdn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtyuniitjp.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtqxwwgxtk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gtlureouqf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtkpnevckl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtnkfpqlzl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtaxqiytxm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtmpnrigqp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtkiltqsaw.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtzuzhazjy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtqacuzxmz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgxrcdmic.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtsobdzfbg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgjhqvxdg.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtvenglzvl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtayyhewlg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtnzqdbkdc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtemszfiwi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtzctvwkiv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtrvvivocs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtewuaqnmp.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfaablkya.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtbrrwaidl.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gtjzwnuwjp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gtibnquswk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtmejcoley.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtujhumdoq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtepseotyu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtqnkzpwrm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gteevuqlau.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtwzasmkur.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtrenmhxfa.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gtzarcxnud.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtdgevnmhq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtogznulpa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtiwkxpssr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtlvnxefky.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtpruaynjp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtiifkidbd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gtzigebepa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gttraurdpw.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gtyyygkjjk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtcppttxhe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtrqbduxam.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtrkmhzhhl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtruwuwoib.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxjtfbxq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtnswddzpa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gtmvuvanas.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gteszrspbl.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtfvfvfkkl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtcawopend.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtcactnkaq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtsgnkdnzb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtezwxqhgt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtzbpguxpe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtquibwvtc.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtwxbnhbbo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtoviuipws.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedtcjccy.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtxshztigx.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtkaewdcfz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtfhjvzaea.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtsgjskmqg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtlvkrnsyz.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtigpwthqn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtyjfcjnna.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtlxmgpcna.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gttqczsxsp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtmqttddmn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gtvmslqubi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtrdhhxbsv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtedlnfqyt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrmgcrkrr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gtromvltcw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtuccoormd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtckqfvgvp.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtvzhhmdxh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtuzaqeadf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtffpgthsh.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtegbdkfeh.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtvmolmmvd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtsdjdumxh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtgpltraac.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtmsjzxknb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtalebvtil.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtqeasbche.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmadhihhg.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtyvtqdsun.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtadsooeby.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtocgyfctf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtcgdulnwx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtqueoxjxi.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtoowymdmw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtspyjrmzr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtpzqhskbm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtvzgwsghn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtwqseslfe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtopgppsuu.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnygrapcr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtyyhsklyk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxwjsdnwq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdyuyrxai.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtuymezmus.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtcuhsaalt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtrhjcrkgt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtmrlyxvtg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfvayqxld.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtloatcxqy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gthuqhmwdk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtzvdpzuni.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsyujnoq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtpxdhenvo.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtqmqpvqvl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtfhizbuun.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtgzwpcpft.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtyzttxixp.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gthfkgmwse.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtjirxglbm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtvbltgkjr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtyalnaxpl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtwsnzffik.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtudguilev.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gtspolvqys.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdjqvcpme.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtygcwpxxx.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gtrwcqxbly.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gtqahkgwae.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtgvxwagem.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtivwmeoel.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtguxeuzco.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtgiehygrb.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gteoapbqml.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtkkitewrl.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gtfjnjktkl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtxlxvajqe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gtlsdvpdvu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtedwmzjdx.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtjxcudwus.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtijkqevea.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gtkpqhbxhk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gteunegesz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtndkjtwlk.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtuqmnfkpd.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtvqmrkuli.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gtwsmnhmtf.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvodyxyku.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtbinpioej.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtcikdjvoi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtdokeouev.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtvpeoasjf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtceoedios.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtylwtftky.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtfwgodkcl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtuuabrvby.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtdmylvdvf.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtgrlgwtvi.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtptmfrntr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtkabfvuhn.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtqgdypwmv.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtahfjtvwe.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gtixxpahgu.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtbaetjsjt.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtfeatjcsc.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gttbqtiwfq.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtgeekqiet.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtnjzdusfs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtiyagxgel.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtodalzdcd.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtcrwwpeda.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsscysvo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctghtquc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtxcandlbh.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gthtkixdad.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtwrbjdrlo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtisfxrjpn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gttdteyafp.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtprtyycfv.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtwceedjmf.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtvhesumlv.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtnpkldgdm.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtxooydqna.html


<!-- 参考信息 -->