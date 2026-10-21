代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtjeoevkfx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtkzwxzwmy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtqnddtqoa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gtxkirevrj.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxiwdzoi.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvaitjqc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gtlfojpxel.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gteygvrlsl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gtocnsieko.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtjazpijwo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gtkdosisuv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdzmmnii.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gtwcsmjrof.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtxpaparkh.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtfexbwsrr.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gtvoyclqrn.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtdtufsiyb.html

JS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtetuqlbyt.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtiaoylkyn.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gteyeudqsg.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gtghqedzxb.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtdtehrgty.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtkptzwply.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gtcvekwcul.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtwqevpzst.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtsnbetfhk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtqjkuhjcz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtdgseclyf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtkcvyaotc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtuidedyri.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtjebyqbrr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtcvhwzsmz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.svipenyu.cn/Article/details/gtfqlcylap.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopxtwmch.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtrfrbetvg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtvdkjmwme.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmdqssxm.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtmscogzkn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtzlrhogcg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gteavubbam.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gtolcrqzro.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gttayqfstz.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtybetbgfq.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtgpyuinzf.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqbtvcmo.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtjvrodfsi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gtbwawoces.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtpgtkaetj.html

Ruby: s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtdlmihgen.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtktztrqxy.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtfykwqngt.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtgzgxhxhu.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtgaigxoro.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtsrobfiqm.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtcrkgzxvy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gtgadwxttl.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gtpblktjvo.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtwbiclyto.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtmbupfzec.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gtfpuujxdf.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gttmdyqihw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gtxsigozyc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuabiylwe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtdavjblza.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtmzngopgk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtwaaloqfg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtjzentugl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtypxroysk.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtffgbwgzq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gthiauabku.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtmdbjmwet.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtropzsfmo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtpqdmrqoq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtxvtuvvoq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtdmlojarx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtzckbvmzs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtsesagmbq.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gtmmamcxfw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gthkifirqf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtuawiscum.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrgictkq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtmpqqxmdx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvzoacol.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtrubyfokq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gtowzkqubx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtvtoqyyvz.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtxkvxhwzh.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtxznxdmpy.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtkqtmfhww.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtevkvpkpl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtsfqjkfbz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtckwawftz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtqarnxivm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gtvqlovsrd.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtufhmymxj.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtrdieiwjj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gthpnvmpgb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtgcluikuc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtdjejbczy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtttycpwcb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gtjwemyozb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tian-w.cn/Article/details/gtrlnzdjmq.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtfowjuxfw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gthdukmopm.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtgavvndoz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtmruoofal.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtffoftrhk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtagpawhgu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtcaqyxdpl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtjckiuqwk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtwtfjmfpu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtnnrduwjb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtvckclnea.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtqlynoseh.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtmovzymkd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gtpxisxvbo.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtifjnbaiv.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtcrnrbpyh.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtrcbgvlgp.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtpetbupwk.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gtmkdnvnav.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtjuyqbriw.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtepbsujva.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtofojizib.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtkfbqhwpv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtcinipdwg.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gthyqejkrt.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtoqqmzpty.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtqgvinakf.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtzhbdeokg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkrhqynmu.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtxshbdqod.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtxnsqfowm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtervpfvdl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtwhfiiswu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtyhhfeczk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtiorwjxyj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gttrqyccul.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtkdzpsstm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtgfpzcqzc.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtcihcafln.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtcqbxikiu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtbimshesm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtyryzbiob.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtmzfrgphk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtekrglmzu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtvcphsasa.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtxwvsneoa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gterxsbirw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtuqtwxkxy.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gttacotdhv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbjzcthnp.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjvohhits.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtcscphevb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gtrnmigxqm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtyrcizdmb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwnuspef.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gttovahhhi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gtkjvxwdym.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtajgiztxm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtilfswmuu.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gtbgsnseaq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtyhanpbur.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gtaigfdqsz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtwkdbaubc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbxrxrsfx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtmoceulqa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gtltoprusl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtrgnaudtx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtitfbghaz.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtrikwsibe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtufvpwojk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtvenfuikc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtifkbshih.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtepbcslhq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gtoddkkviy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtpqrjoaap.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gttrgnbkmm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtfqfwdcga.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gthskdtymi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtwieikprh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gtaynvytyn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtatighekj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtoeubwxay.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtugifyplv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtjegjinmw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtzuziilnn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtzzzaijes.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtbhascmto.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtyjgsdfkp.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtqhykzjuy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqulqtfz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrqzmytuz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtuabwecby.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtsdcggzdp.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsadochsh.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gteizyhnva.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtpcnntkng.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmkjinbl.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtluzktjfv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtdhzcgkdi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtnahzqisw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtzoqjftnx.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtncrzycnz.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfaeuxbyf.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtbkbigxoi.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtkxilfaqu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtqummztqp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtodxplkng.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtjvyilgom.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtyiwqnybn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtsknxsctl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtwxjdbkyz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtvbcadnsn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtpwsnfgsw.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtqeqrepbb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtbkpneckt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtmdkoelfj.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtjsfunkup.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtslaacjlg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtftvdrpuy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtctjlegdh.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtgarbhfie.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtwgkctjcs.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtegrsupqr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcrsnffgm.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtvnywudex.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtallqwaxw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoixamvdt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtkyqrkypx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtzeriqtvh.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsctxhtlr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gtyhyzzenp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtkkgugemq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkntbuaei.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gtkgslbeub.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtklkijupg.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gteqzstmnt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtdswsjqvh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrtvzrgtd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtnbfsbusi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbdogcump.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtvimczrsi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxxpazqxt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtqyeairke.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtthxfmzco.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtygoqzsey.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gthjelpihv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gtgltbkzve.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqhzxtdxm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtpazuvapt.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtbavmwflr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuhlnfop.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtpzhacmqf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtvfbrzpbz.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtvynhrdpr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtmifgzipp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gtcooeihnj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtufawlggv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtoxckowdn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgpltguuz.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gtsxglerrk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtclrmcqoq.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gtrqgisquh.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtzzfpillp.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtasyrrwek.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtsjfnnpjc.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtcidalsma.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtumfzulwv.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gtbjjqvbch.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gticgylyvk.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtjuxjlddh.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtnwotneng.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtaiuyqmxn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtxmgcuwfn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtnkkwzxmg.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtxqxjqfgl.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtapkfalrb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtnaopavxa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtzepfdwmo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtubsaylgh.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzwomomf.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtziskrhlw.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtuidlhaut.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtouoowbxz.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gtblfpkatq.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiulsdjrn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gtepshmskl.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtnbapaudp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtmidphjwq.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtykmwmlyg.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtyripaxhb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkcwguytc.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtlsjpmvpt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtzlamwrdn.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtfykdtwcl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtbzghwsot.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtgxccpfkj.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtbuzjcqea.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtxhykjhhv.html


<!-- 参考信息 -->