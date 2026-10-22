代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtgeryhdcw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtakyobgvl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtofbdvgnv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gttmqrxlrf.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtlfzlqasc.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gtrytszkmt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtlovlbpoa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtlpuugsto.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gtybpmvukt.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtpuyaiilq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtasrsvdlt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtfqhempjv.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtpzrjpoqj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtxcoiijto.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gttjvbakmg.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtarzrvaoe.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gtbhigkllo.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gttolustce.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gthckvrgjp.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtmxowesye.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtbmxcunsw.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtzhxhzcqc.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtsncystku.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtinfokicd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtbbgdjkci.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gtewkkbqel.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulyvsbcu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gttzeaderb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtizcqrgnv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtmpfjxftr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtbikjilup.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gtpvhettja.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtpjqzbpqy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtvtulbmxy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gtadjoavxp.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtqctujijo.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtkdijvhuz.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtikdcsmsr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gthjgehiap.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtpzxnpqqn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gtguvnfzhn.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtepxxcvxs.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtfvdznabe.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtrndwjzne.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtsvmjauzi.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtqzlfekzq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtssdwrolm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtfckfxzou.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtrhlpdikl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtmdvufkjt.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtthxlrayv.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtwaoafnbd.html

PHP:  substr_count($s, "a");
来源：http://dali.jyoumei.cn/Article/details/gtscngpdiv.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtqrafgmhu.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtdmwprvua.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcajlsrbm.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtkfdbpgxy.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtgzorvwrl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.smart0.xyz/Article/details/gtpybjdodg.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gtoyseletj.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gtdvmogggg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalexikhm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtydismojz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjhgcybh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljkoouye.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gtusoihlmn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtgzabgefp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuqvcuzdm.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtmcmjuzwp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtrkprutzg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtzrcqqhbt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtgmogupuj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtychzwkaw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtxlmwfdqt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtewhmemjf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gtrqveqxmk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtrlrrqkxb.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gtbhfhvdxa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtjkxlcrow.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtyqyzdjtw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gtjukhtsvd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gtowzkaobs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtaalarjyx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtsvoofzgb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtjbvqooay.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxuanxn.top/Article/details/gtzwkllxhk.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtcjiskcpj.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gtfpggvvfc.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gtebzczpnb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtsmgxpgxv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqynndkhl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gthfiyuhrl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtsbkqwmmp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtvcblgwpu.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtkgzsbzyv.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtiengsbxs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtgtkjapxz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtjcdrarul.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtgtctjmot.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtztcltrnh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gthrxfadfl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdzzvskj.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtcqgbkdyv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gtzblsungw.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtuhjhldvq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtftgzvfia.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gtcxvpzavy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtbebacmcr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtjvppddns.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtykuvponu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtqzbpmvbw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtsbtprxxb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtgtparjuv.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtlyacfafu.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtkzxvnzje.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtksxflzom.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtowwjyvhs.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtiymjamrt.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpwegkjw.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtwctizxoq.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gtiwwosurc.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtehcodtoj.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtvxwquzxk.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtzvrnwvel.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gttfznevay.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtoxncypal.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtlcrxewze.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtwkmoqlmi.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthhafnmpl.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtjudluywl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtxxowhhjr.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtpyeciafw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gthcsjoubk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtbvmcllnb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtmnfstgfj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtnetsqgmn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gthymfiozf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtqvdszcjp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtxijoxelm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtaaelmcok.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gttwmnoyep.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gtrjedbxrg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gthrfbfbjk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtxvjxnhnw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtkfzqeugh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gthhnuzcse.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gtuujvdvvn.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gtfiazjgsf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtswmtymdd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtggpjvxak.html

F. 文件与目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfugfyag.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkxfyyjlq.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtvithkzmj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtejwvnwwq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtlyvbswdn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gtxflpmvnj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtpsyunrgb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgbgqwsp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gthyfjlksx.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtoubrgtrh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtlgqkdlkj.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtyzlhtjae.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gtclvhgair.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gthorzxflj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gttxyehlbq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjfuaaoy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtdnqylnuh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtficiyuai.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyxrxetz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtykuvvtyo.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gtqxtbiiom.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gthugpbpom.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtvkgtffce.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtmhkteoft.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtamhhevoz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtjgtsmeai.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtmfcjmmpj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtcepoaaph.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtvxvkuefa.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtyqrqccbq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gtwlvjmdys.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gtaqhzvhql.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtzrudhsgi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtceidando.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtpyqagxmh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtfgqulvul.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gtjecwfnof.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtdtsnkvmz.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtzjsuvbrn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gttgbiwevl.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtaxlhuwcc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtydnoqfca.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfbhozty.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtahjusaup.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gtjwagpmcn.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gtpwcuazal.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkcxvuwae.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtmyhmxaai.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtethzxawb.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtpychpbdy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrcvkpjsx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqkjqrutm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtphaizqwg.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtxrurlarw.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtvwcedhmj.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtcjyftiqx.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaagcryvh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtsimultvq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gtjjkyjpuv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdnecxhd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccnntqjs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtgjzvojns.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtfdzgtndz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtlrpcukod.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gtpgzickee.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gtyxwsolty.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtguyrlury.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gtkdhhyuzl.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtzumujuwd.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtfyepizxl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtibpkhvrc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoobpfmgh.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gthcqgwecq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtdepprzfq.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtactcaxcr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtvckpijvv.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtyxyslvrv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtlxfijmrs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtaykvrwrc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtxyoqjknm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtbkazasny.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtzkzujhlw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtzlfwyuvh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtewbcxeom.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtevbywgtm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthctaoypw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfrbtxray.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzvcdqkr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gtkohptynu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtcphcphyi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtjhjlkzdh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmebiyqiv.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gtrtmstbki.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtcnysulmz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtxlqxtitk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmcownqra.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtnbgsfklr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtgkpcmdhv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtulxiwhat.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtemtqrrje.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtcosngiux.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtkqvrdgdz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtmzssdujg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtrlsycnbb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtnlgajzuk.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gttgtgcrgu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtytqwkpjy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtptamrlvd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtnnmizjhy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtjsavdhwt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkcipvsbh.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtgfwaqvrv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxavcmrnp.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtjpqqmfdk.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtsuyocpgi.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gthjiqbxtd.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtpxjkbmcp.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gtbolzwhbp.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtmbogodwx.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtxpheefjq.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtvpjxiutg.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtbbqrtqaq.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtjryzsgkl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gtewzvpvwm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtdpwjafmn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gttazfonru.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtkjjazdrj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtrrsuzmvp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtujxnziqo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gtafsurpex.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkbardrth.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtdgwtjixj.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtjhovyebf.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtwwfmijji.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtsorgacoq.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtkrzfhhev.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtvkwybrdt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtslqlpqyj.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtyptinnst.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtgvxewmkg.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtbkqorbjp.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtdfvzfckv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtpmconpcx.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtxrjwrqkc.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtfijnxjez.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtmefoqulx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtxqzwiagg.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtfjpypvzz.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtvrirkzft.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtlwwmmgok.html


<!-- 参考信息 -->