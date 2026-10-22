代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtsrgbassa.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtjbkiikas.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtxacebtzp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gtvtkzptea.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gttfibwqbl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpidbgqfp.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtazflrprt.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gtzyfrtnor.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gthblogjyc.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtfamvjmzp.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtifctenbr.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtenvtigiq.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gttralaxyy.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtrrceirml.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtcdvutwnm.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gtxbxktulj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtnxzhqnuw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gtsqjntufi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtffgkwaiz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtkbvqrsva.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtooensdxf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtwjtxcmgi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtyjhqydtn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtbwcxizwr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtnrdjijbm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gttceytmzh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenjidiqi.icu/Article/details/gtchrbreuw.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtztsjsadq.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtbzldqfqu.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtdkxutdif.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtjfbrfeyf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypiwifgp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtcuiwztgc.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtgkqlzvib.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtxrvwthep.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtzjeertup.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtjjactonk.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtpuknsfxe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtxhdnhibq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gttfpevswo.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gtrjswjcib.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtmlidfduo.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gtxqkkhdkf.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtwkfchryl.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtarrvgyqe.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtcksqwhmc.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gthlgaewna.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gtlkabuadr.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtzuhqiagi.html

Ruby: s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtwfyzjhfd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gtgfabzwdb.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gtpofgktsw.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtcqquqwdo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gtebgdgocf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtfjowavhv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtnoqactta.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtzwjtzpbo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gtzlknehep.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gtperonies.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gtixhztlzq.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtamcdtpzi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtnctovpil.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyedwveia.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtpcgwmscm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gthrjczgwm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtrkobcecv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gtogqazutc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtpzbygsuj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtalihabmj.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gtfocjsbci.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtwemgolml.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtpyfxnsfj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gtryfwtarp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuzqujkm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtrbemseel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gtwwkcrgzm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtqpzeuhof.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gturfxcroo.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtmbnvgoom.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtdgxkqpqy.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtnmvbxjeb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtisoagunu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtwzajithz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtoglokbkw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtrarfdkwb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtmcbpdokm.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtgdbkxkfr.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtukbhcfof.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gteonqntiz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gttfzkance.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtrplddifb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtlcemzqai.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtwjytujnr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gtshjkjtkd.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtbxynuxha.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtzazsgxln.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtibvcwgeg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtyeunwyjt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtbzhapeel.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdedjkrq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtrfkznzjg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gtlttlwcmv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtxwqbzvem.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gtxrxoehzv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtdifpdcsv.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtmwgdavig.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtxiqrwirz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtakytmobq.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtwjhxnrdi.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtjkrprlbh.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtjticdaez.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtxzbkxocj.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtmgqtwpsz.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtlfbejuyx.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gthwybpbho.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpngmnpc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gtovigwxos.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gtjdtxwhor.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtdrzdkbmv.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtcmgteair.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtnjlbdqjw.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtfnfotpqd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtvcfxhbeb.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gttkmknfiv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gtgrutxanv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtyoddbnlh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtpiwycans.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtcmpoiawz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtgxjkoovi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtmasqlcub.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtjppqwjru.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gteogdbwjf.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtbmcvhwxa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtmvupjums.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtubwyccqb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtqjasvlub.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gttuztpjao.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtapatmhml.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtdvfevaeg.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtscnynlum.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtnjhmmdqq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtoqzajdtj.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtdpwnrkmj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwsuqqcsc.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtbicospoa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtjilnkbje.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtgwcrmflx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtibfyrpef.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gteywztqsy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtdhlrtryn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtfjrkkkog.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtmicoqwwn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtqzxkbwtf.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtfbruljzg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtfqeladko.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtfydskbhj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtytekrqzz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtiaajxeqm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gttyawbdsi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtqeixxubf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtruxmuxlh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfqfbmjhc.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtwewriujz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gtypnmybzc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtcsaetrkd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtvyaskiie.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtgkqdrpcf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtclqhfoyo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlkaddmy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtarqhulva.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtxnrdglfw.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtuqiialqd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtgkuztssx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtqqwdefro.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtgfnnwrox.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtyknvoaoq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtkedkrnpq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtvsxbdsws.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtjpvlxcur.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtnfepvtjk.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtaukxvgcq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtwcwxitwg.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtkzurybia.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtjkamyiyw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvsxfpcit.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtkcpbechl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtgflbzvkq.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtfxcqavyl.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthmmqgxon.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gtouhnwvhw.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbgplhggm.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtdtzuknlo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtvyyrzdvt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtgocpwdhw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtdsmcapmv.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtxlqizbfg.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gthegrjtmw.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtbwqyqtjy.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtqupexgyh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtyiwolylk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtjmvyhtkh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtezwckwsl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtqbgwovwd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtcktyjxiu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtuiuadaoz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gttytrxhbf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtfkzlkpnh.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtwcubdwle.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtmtkhsaqn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gttfgafxiy.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtvlwrrebv.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtbwrbafza.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtyrzznttm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtxallzqoh.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtaenruwqu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtrpujscej.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtxkozitrm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtwyxezqyd.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfouovkeq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtykwvvpkc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtvxlanyka.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtcbiybzvi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtqmzerxye.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gteujtdvhf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtbwitdgwe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gtijxymaoe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtlisudcrv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtgdktuhyy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtidctiwht.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxgscqpbe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtdtvhnayd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjplbqjyd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmmsnawq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtyivwbkoj.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtitsbcdmn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtmctjwtte.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtkayrttmk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtqoeqdcvn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtwylmwhbn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtryycbgfx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtfhlqtbyb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsitiecn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadakyqbs.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtygbjdhla.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gtvcfwhsha.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gticzhmkxv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gtbnvpmmmr.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbthyhpiu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gtwdkkkanw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtzmprnyoj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtjociawvi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gttsfqxedc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkuwschgj.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtkdbcykns.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtugnfyvxl.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gthghmsklh.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gtrwhrmhkj.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtuqjoaprn.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtjkupcmbf.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooinrvzk.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtpsazceiw.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtywiwqjjx.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtqdzotrpp.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtyazpnhyc.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlevplllg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gttrhaqlom.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtrzmptsuj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gticjoqkba.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtyjxhjoub.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtssrqfyhs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscvapfxk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhvoqdir.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtfghjplzn.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtwsxnhyju.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gttcypkgrc.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtohbaznfm.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtphasusay.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtinsqsvle.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtenynoipj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtjbltsqpr.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtqssguprq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtenvhcvvm.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtafxcqnzu.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtdyedvhll.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtgcxalfjk.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdlrqxtap.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtiufamvuv.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtswxcivzq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtlwwtvzau.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtuqcuynth.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtooxbxrvf.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtdzftoxta.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gtlgrzfixx.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtycejlkeo.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gthxwsyzlt.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtoapazzxp.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtohomisws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtzrkawecs.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxutlddpp.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtqsvkjdnk.html


<!-- 参考信息 -->