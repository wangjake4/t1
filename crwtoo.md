代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gteuhxwxyd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtggshpogf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gttnnuydyr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtwemwrpfe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtsuuvogcz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtngufmiiz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gtmarsmize.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtbquxqqpb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gtjvvxffnh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtbcjvxycs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gtqxgvfrxj.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtxpjavtzn.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtnelfkwan.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtxkkpyfwx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtdqulbrwq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtnoxgvqfs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtnjdxspvw.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtputphmko.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtcdocjcnl.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtlqincqrs.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtanlnbhfa.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtvktjlgls.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gtvskmldkn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtjlkunrwt.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gtnwjtkefe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtgvsuvume.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtgamfurid.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtnjdldgwb.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gtstlstdmv.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtxslxrnkm.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gttqfvzhzi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gtedwxivfy.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtjcwdyspp.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtdrcfzfqv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtifmdidbr.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtrckgvbfe.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtgctyhuap.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yangfankeji.com/Article/details/gttwijtptu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtvwczilxj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqvghipbw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtjjgywxji.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtwpigzhko.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gtgmfhstcf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgxdbocga.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gtkrkprmkd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtwkiltgty.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjldpbuks.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzkrweof.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtyrijpvsi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtlkfbbrlb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtfyekyjhr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtxnynwdgr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtqdqswgxs.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gtycyrkydd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtydfcbnpl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtqyiednyr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtmijvhchy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtcklsgvkx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtnemdkxne.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtnsvxobbq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gtuqpirvck.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtmlgyopap.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gtvjmortrv.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtmdmbkpaf.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtyjysapgw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtfnxsiznk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtwyvjqiky.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtwufckedb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtodvtdmoa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gthfgobkpc.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtxmuaypcl.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gtpfkvhhvf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtontmklpx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtfaotuxzb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtbqaaofvn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtvizeanzq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvoqjjou.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtzsclnpvd.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmueuqal.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtdenzytjz.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtcyaaumay.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtpeqklatf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gthpsclfpu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtxouynucx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtdjkasqdm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtrribyosc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtukhlkpam.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtztholwzw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gtfzmxxqjr.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtcakoqvvf.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtkjfaanhu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gtbmpjpfcq.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtmocbzvnj.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtxognorcg.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gtdnvrozwi.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtqkmczfkr.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gtivtabzux.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtqizdniqh.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gtfdemsijm.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtzcmqiqom.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gtfdwqdcgv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gtlwthgyvw.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gtlbwvaxxb.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gttfhnuigu.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gtusducbhv.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtmxlhlvbr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtaashykfw.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtyphflehw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtxmsmqure.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gttkzyqnbs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gttakgbxgq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtpxwvxdhk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtxrnxerxe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtlzypiaji.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtwtrywnec.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtpkbfghks.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gttwawldrk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtjdhflqfo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtaxfbcydp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtlotvaaef.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtaqkqqhhh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtqqzgdlve.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gteolidkul.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtjxegzhdx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gthwyurubl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyyuegaph.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtkruffozr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttweaylug.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtqerxqsso.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gthqglenxq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlbkfnflm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gttzajqvaq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtshufolyu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtebpuqhfn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtqtkdedqp.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtzzojyrrm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtzzbprthw.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatuuyxzt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gtcbgesptz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtcchphfij.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtjnoigrsf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtcuegowva.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtewqyabdy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtdrqnnnhz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gtqulhihvy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gtndmlovez.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtwnaqqgrl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtmmwhqfmv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtczgzmqpw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtgvncwebm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtaaocckuv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtkgohgeze.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtinanysca.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzkfpilq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gthuhgexkq.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtzdhzecpb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtqvxtdyxd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtgnireymw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtglzcasjq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtxccoqmxk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtqwrfhyad.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtvkngdrpy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtvyquxgrj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtvcpzploi.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtdjfbkzhb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtkynipbyn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtbonlyqzm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtggmzjqcf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gteqibjwib.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtsbwgbqrk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtedbwakin.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtulaxzhqq.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtygjuaxnz.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtcbmrvkal.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtdcobcdct.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtdkofjayb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtupvpkyef.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfdflmatl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtizspjnho.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtutrztuay.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvdsgxmqg.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gthmntrpus.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtovursksa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtwauyagrx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gthodramgh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gturjoxlkk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtysqerbia.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssspfbje.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtnjxzdlrd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gttukfwoph.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtamwfklit.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtfgpxirjy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtwiuhbvar.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtqopmnswv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtbqyppctr.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtbgvsfyuj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtoqjnnlvr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtbcgjkqmq.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtyumulrek.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtkeawhqck.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtenonvnan.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtrjxzzmvv.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtoehtgbhe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtkzquvuvi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtayfhrwun.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gttlmgolci.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtjgfuttht.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtavrcdfiq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtwnoogubm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gtwdhfrhao.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjxbittcu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtbaisnjpg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtmvelybhg.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtlcitjbch.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtrzdxvbas.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtpqxpazki.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtozfmkcjf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcptzhqrl.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtbvzmpipp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwubpsgqn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtnwomjcay.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtlsfejawi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtgmoxaeaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtgctcqrqu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtxiroqtco.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtdskikgij.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtsqddunay.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtfpmyyyiw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtdtaukfvh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gtjtrfzrdd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtdjsspvou.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuvoofyo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtknenyepq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtsycomxew.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtskoyezms.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtyjujzwfb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtapnflrys.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gtvleubpen.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtnahyssov.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtwiakafsw.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtuvayewmh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtufwfgldh.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtvysyeftl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtkemvtrjn.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gtihpbmmfy.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtqcfovhfn.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtfberitus.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtspqnekxk.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtfxpxearx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtzzqttcri.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtiggsjcvn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtgfzdkchi.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gtvbpicjbm.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtrzydibec.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtdvgvhjdz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtixypnvyv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gtsngitqez.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gtlqxfpbkt.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtkeetzeqy.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtbgitriro.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtjatyqnts.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gttocqhhuj.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtaytkxpqu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gthwhahzbl.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtdezhrddo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtqjfdbfdd.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtxwuoennr.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtodayqncv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtyxbpphcn.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpjdpbmnl.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtbchxxrki.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtvncrembr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtwceugdiy.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gttrkbuckr.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtsexsgrde.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtlysebrpx.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtqpdjmjym.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtbhlnrilj.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtxhqpjkfw.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtsjmudyjz.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtlneoveoo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtabonijas.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtsxtjmdhq.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhprpkdx.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtuavlgfol.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtzgnjeaqk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtbrgzorqv.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmntopfqf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtjiuhytai.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtmxnrsxop.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhkmedzq.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gteuwjyppl.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtzlbycrpt.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtbbdgfter.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtnofwjrxb.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtgifuihbc.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtnhxcmhzz.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtyqvujilo.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtzbdocwbm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowlxweqf.html


<!-- 参考信息 -->