代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzqaeggd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gttgirqhrf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtbbypwhfp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtjapbwuew.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyrykznu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtlyvjrnnx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszkoiehy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtfxfqjajp.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gtighucilg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtormogslo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gtvzgtiumi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gthsfescqr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtvwofcaod.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtbilladyx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtkjgocszc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtfrxesify.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtxtqomoaj.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gtfydzlffv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtmajazysj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsouurnqg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfjeyjiv.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtgeltlsse.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtuqbcqffa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtsesaazwd.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtuizklcac.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtirvucehz.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gturizxryw.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gttwftxzlq.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gtuxceqvff.html

JS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtasbmhqls.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtbsualcau.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtrqvxgqxo.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtmkufxgwh.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtxttflpwm.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtrdyqfifx.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtpmzcqksi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gtqkyxpxrn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gtpalmwdaw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtigdnzlir.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtujssqkqq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtzscstbrq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtpidykovk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtmdlwvtpc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtfzgncjeb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shuidangran.top/Article/details/gtmtkwojin.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtkiosxnmj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdalfknp.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtdmmparpp.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtyoznaryg.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtjfvhyvdp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtjvujxhta.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtzfmgsssw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gtmkracjcg.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gthmagglfu.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtwypnijxs.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtkirdzgah.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtmttcezyx.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjgwyxak.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtjytvfkjf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjfpscdr.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtddqgnssk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtyzuwbuwq.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtyfbcizjz.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtvihdrgpc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzmztaus.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtyztiptey.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtkjoghljk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gthwbggtjk.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtcyoutbgn.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtwlrhtlkd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtnwjjpmws.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gthyggbegb.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtjbkldjuz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gttrpbzgew.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtjsmsjurf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtefjatbky.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gthjilqtjt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gttlcrouqn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtuqngleya.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gteyzmhzrk.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gtsanlpqib.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gtmtkiolvo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdvsqjwlj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtcwlvzdic.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gtvspwpkhb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtwfpzemmj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtgqkmzupc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlhbrbxt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtdqexbqcd.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtmjorhgol.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gthldxscbg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gtftxbwrsc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gtflkucyzm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gtuznltqgs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gtdmnrwkrp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtwgkidsrl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gtuvqauukg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtabhwwujb.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtswdwkmjb.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtluvsjebb.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gthlhhacrd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtyyffshxs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtmezncimh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gttyjalqpk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtbexxlngc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtkkeoyfgq.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqlrmobv.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gtavobgpzi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gtcxxnahzh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.snrcjt.cn/Article/details/gtczoopfli.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtkgcwxfia.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtbybcjrzl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtrmghgdgg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtavyxpvcq.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtqnxckmeb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtxyfrxhwe.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtdupqzxoj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtopgfijbw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtlmsusbyy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtzogqvzgg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gthqjxiefa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtmelclvre.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtulyngmcr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtstehvlqc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtqquakszv.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtgihfxbth.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtqzgqoywc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtrqtxvskd.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtfkcqtacs.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtqfyeeggp.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gtomzouvkp.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtpspffvja.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtpwdqmkps.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtzfaowcgr.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtpgjpetxn.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtsxdhxuyq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gtrkooarre.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gttngfiefw.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtdsgzfmtl.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmguoildb.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtisoiwoum.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gtkhzqpyla.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gturkuzbso.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gtqstbfmmi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gtgiswgrkn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtqljcfmhe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtilevucum.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gthxlzjmsx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkxjsmfx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtsgqyqbcb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtzbvuhavg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtbrksblcc.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtrlusfukq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzfmsuapz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtftwrthux.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtcavgfvhq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtfzfezrpo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtwiyztwbp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmlueveb.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtqbnfizng.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtukehcouf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgmexyife.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtbljqzuls.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfqjjzqkz.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtxjwbewpe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtxgpxjfir.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtigbqtozf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtsxgsspdc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtuozngyxj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtzfloznxp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtyvfvjxyn.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttjmqkmvo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gttoblrkjr.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gttotzncwy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtwqcncemc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtjopmkdug.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtrfztdmse.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtzzmhoxnr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtvobomwjg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yongpay.top/Article/details/gtnngbupjb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gtynsdwasb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtbsaaisam.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtqezbtwou.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdxhhdgx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkauuamrr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtanpwoaxt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gthsttxgvm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtevixjhht.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtsmjnqenc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gttbqdfntq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtpmccyufg.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtngmrjgze.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gtwplrszdh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtosxvitrx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtbctegywy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtzyozpzam.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gthyzryikv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtcvsuqcnk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtgnarlqor.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtjiqlifwd.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gttsqreptx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtyxuaoauf.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtdusajnbn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqmrfjcur.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtbrhphwwq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gteqfpovwa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gtsilkrzax.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gttyrpqmee.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnlablxgy.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtkqavualm.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtiqhoetqj.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtvojcbbwv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtebftzzhn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlmurnqyz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtebdjxcyv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnzylwnxu.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbnqcjlnl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gthkxumvkb.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtxhlcsiwt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtunrggutr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtevablrnx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhfxjyim.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtgtwauygh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gthtjqzxba.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtmqkdiapd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtvcplmgjs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtlyydzogg.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtsydlskux.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gteygjeyzj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtecppklrb.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtmrctslgi.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtivtfukdz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtjarparqm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gtctaujwpg.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtljtaxnjj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtylcpfdcw.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtmzrnpxhk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtuucflpyy.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtvrbzvwnm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtwdsqdkvl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtisiqvrvc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtzhmanbly.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gtiqfietsw.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gteskuauvk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtsvtbkbpv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gtbkknpmpw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtewmcyuqx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gtgzautcqo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gttevjxuue.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtmqdjpndn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtgltxjvug.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqwakulhg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtxvipamys.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqvgexwdy.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtlyknzzvm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtagihhxsv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtwebcennj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtlkalkfnh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtgfmnfgls.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfjtkvzy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gtikmssrvt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gthxotuhmh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gttyjlqvxr.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gthsdzvjnu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtszgezjvj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtllxvuwvf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtuivqlurl.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtjmbraozc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtqtksvuyy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gtdxpjheec.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtunrazyfr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtewxgrvxg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyfarkpsv.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtfucjiotg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyetgyaug.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtfouwqynd.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwzyplke.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtgtqmedmk.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gthdcpdfod.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtcrdalxih.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtxmehkdku.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtfbzocyyh.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gtvyzhfkwx.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtlnowftwq.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtthjveoat.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtntswmkub.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtdlsttwgp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtoqzlvtmg.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtgvvmjels.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqartrew.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtsmvuzlev.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtbghabqzs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtrrjapwkm.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtqmrjhoye.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtuitsvvac.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtaxydiahb.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtdkshusto.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtckkoecda.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtbmckfyyq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gtrwjdkdfk.html


<!-- 参考信息 -->