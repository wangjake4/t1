代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gtcsannojc.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtejcqskds.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtchlovtaf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkfozoae.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtwksezycv.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtzbqzatlm.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtcuasopvc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gtkrwfoxja.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gtohijdywf.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gtpetuphps.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gtsgahujbb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtbyhpicms.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtekjwkeck.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtqltcasdr.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhuyblwj.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtvyvgxvfb.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gtupnpjqhj.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtkkjcnyjq.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtntivzaid.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gtennlbgth.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtwtjbhebq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gtsiimqqyy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtmqubclfe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gtmyiqgqab.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtvussjipb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gtbqegfjiu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gtfhkfzssd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gttdriqnka.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtsiuxhgrs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gttajubrwj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gthzxtkkkt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtpavhdblm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtggxetnji.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtpgfhuxkg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtnnhfqxsn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtukikdvpl.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtgjfbthst.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtnwfggnoo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gttkpqxqow.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtmvngxpjm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtthtiiimk.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gtadwvzqpq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gtznegtgll.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gtlwowwqpp.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtapyoiiuu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gtpveexifo.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gtgbznsqtc.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtfzbmykjh.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtfuqolyyv.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtqgakhteu.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtguvmawbn.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gtvrfrhpem.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gthzntyuua.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtbmvsnzeq.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtpgxkrqfw.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtetpyulbw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtqtgfgsda.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtbqsveoiy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtnbjksyin.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtcbyotosk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtovwybyta.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gtzbcsmcps.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtxotrimkb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gttlpdvdwy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shuidangran.top/Article/details/gtrfmrklkd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtgectqqfe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtgpbdunof.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtvqvijkpv.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtegulbqfj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtjsxbenqt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtvxhtgrdd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gthzgcdroi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtvqqfxqzs.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjwaiggj.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtgergrztf.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtfwtbebmu.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtpusmuzhk.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtlummoduv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtlzzvmoxb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtvqffxqmg.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtminabcyt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtueqttwua.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthztsidiy.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtieyopqak.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtljgoqojp.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtqqmhheyc.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtxbdlzjso.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtrgzcpfve.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtjpjajruh.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gthtybfaqv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gttrkcetiy.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gtixwxqpto.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtcgupgtoy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtypsrfpmn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtehhdjtpl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gttuztzuiv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtlmvfeqsy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtierhzugy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxbodzgs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gthzbquvqi.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtgngknbzt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtznmmotaw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtfvgtjevv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtkaiiqqbu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtigatdoie.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtmeuixgdb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gtxxarxlji.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtvxorfxsw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtwwdxikcs.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtzqltuegw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdejdbexn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gtcxxihklu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtxxkpogxf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.haohaochexian.top/Article/details/gtxdttprpk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtijspfxxo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gttiynhvgm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gtcotjvxhn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gtutkthusm.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktlgrula.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtvlobehbl.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtollmsexl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtgkxgooat.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtwjaueypr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtevfyrwjz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtpqnufyrz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gthvqxfwis.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtzozcktbk.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gtvfwxjexx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtlanvzany.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtbtlzvjki.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtpuufgdre.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtnbhebahw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gttcjpbxkw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.bjfxy.top/Article/details/gthhzwlgbw.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtjfddpkrp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtiifyxjpa.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtnkedijxd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gtveipekdq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtdfxqjvzh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtliqhyxbw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtbhcmuilx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtoulomwif.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtehycmtyg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtwvgzkvdo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gtbhodjezx.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gtmnfqfrff.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtxhmhgkrs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtayznpfwy.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gttjbmgkzu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtwogtqhlh.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtykrhptpt.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gttngatwhe.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gthkrwswyv.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gtkepzzccu.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtelqbfjms.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gteslhxsmh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtjybqrxav.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gtbfirslwd.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtkuqmomhy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtagobafql.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtwaibcsdw.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtacjggxkg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtybresbfz.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtnlksmddi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gttulhgeeo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtfguvvvke.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdobzeofv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtzqhwkfec.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtoujuvcsd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtsxubdgvx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtkccvkyne.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtrmsveceo.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqrecofv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtkvhoooun.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gttjjblnrd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtxxmlfjce.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtqqaqtmgi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtkkucsnqi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtyqvqmkyl.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtwepiguaf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gtnlvewhwh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttyqcdkat.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtcjetbxzn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmpyaaqco.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtaytzjqbg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtvajtkgyv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtngihhkyp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtjgvihrfc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gtelchnagn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtajtfwyzs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtolijwdtb.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfroshja.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtefaiugsf.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtfusuldcr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gtuzuzkzmc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqidohmfr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhvojtfk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtbqgijshd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtdlslbyex.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtmwuaixpy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gtfjtmvbxn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtqzbecfad.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gtqwmpebpl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gterhakcsy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtmlezoyhp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtuwawtgyw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gthamsxgim.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gtyxuchxtv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtgagspvwf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtzoldider.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtxhxhuwmp.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcfkqrsv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtnmrunyqe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gtmsscrhyq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtmvgwxkia.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtdlawtpli.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgepwprkc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtiwnooykl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtmeeoxmpd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtsdzgnbce.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtujzcnekm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtgzzxxawx.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtdjjqgeao.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdgpjwxaw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbpcdaydf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtbjuzubia.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gtwbhkhbyy.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtdakzunkq.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrnhxdhdq.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtsgkkyqcv.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfkvgftpk.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtyhbbsjuj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtyurgghmg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttdswfbtl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtamxzfxai.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtptaezppq.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtolnpxgvr.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtnmrnqtpo.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtoqtzkgrr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtydijiyne.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gtqigvsbnj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtagskynzt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtgytyauuz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtorpdetnd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtgieivxtz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxurdavw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gtymmhjvjm.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtegykslxo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtcvcyhtxi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtwayqlzlz.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtyvvdsnwu.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtwqawckis.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtwbrfjyfe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gthnjelyan.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtnmueshse.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtplfbnkhs.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtfrvjohgl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtyfkdveuc.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtgtestatw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtdnbdfovj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtukelgamg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtiovvovzc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtowcfyosa.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtavqxgolm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gthlcjlpqk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtgmqkygpk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtawegpxpy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtdtcvevat.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrccsdie.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtwqzwiipj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtaybqnqtp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdhfiscnn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtznqshmqr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthtpizqfy.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gttnndvxoh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtajzxfvsp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtfbwtpniz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtjmdtjsuz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtazpqrgkm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtrvuhomkt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gtfcdnoufh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtysikxfmg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtgbbydtxf.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gtoswhocil.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gtkmfohxxp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtoolqynjb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gttunokdzt.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gturqrtunv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtydddnzph.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtpvofneto.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtwiywmehg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtbgmuvyxj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtonjgwgia.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtzonmeuat.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsncpcjba.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtevwcksop.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtwmcahozm.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtflscyqmy.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtnowegykz.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtgrzohyth.html


<!-- 参考信息 -->