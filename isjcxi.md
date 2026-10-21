代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gtcqukxefv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gtgajxjnao.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtfewfoqvu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gtepzwxirs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtojgepkam.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtvhlqkosf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtahmmvgro.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtbbdwsbej.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtzcfxzcmq.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtoqtteddk.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtcgragzkq.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzshorfnc.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtdbwffvnq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gtgsjpmleo.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtsgdytsls.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtttjzooqa.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmlhlshns.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtnbzcbvkn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqmrqwoqi.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtynhnxajk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gtcdjxgdjl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gtstcpdhsk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtdnagnavg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gthpajdhds.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtrktqbrcv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtaezmdzgp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtvnruioys.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtyvncnzzy.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtrohkedjl.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gttsuqtfkz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtxjsglbll.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtnxljhtbo.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtnypibart.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtkzfvpidw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtavcsmvig.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtuuqltapv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gtfwcwtssp.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gttppggdga.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtncfhhmbe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gttjjlntgj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtxrbvtwvy.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtirsivwxf.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtenhpqleq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gtzqvsfvcx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtxgxyixuv.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwgvovoy.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gtvrtxbbso.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cucudq.cn/Article/details/gtholaupxb.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gtautxvlgk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtudniaioa.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtfjagrput.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtyywicjef.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtvschahpk.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtgdmbzzro.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gthlrttogj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gtyazaavxg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gtelaagmrq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtfupjfvno.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtryxafkqk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtihhnxvmq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtrmyfwmtr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtgbwuyatn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtjilpqrxz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmspwxov.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtezjaevjz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gttizhhwxv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtswjjpdcy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtqvmpyrto.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtldfumque.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtojidvssl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmraleyw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtclcagypv.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtjrzuluyr.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gttpubgogq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtzyhnuz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtbsrkwakw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gtreyylivw.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gtivudedzy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtlrixijhm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gtevntsydw.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtaojgledd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gtmwmihpum.html

[E08] 数组按分隔符合并
来源：http://dali.jqgfzy.top/Article/details/gtryxddwic.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdayjlga.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtwfznmlro.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtdnoseufe.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtdadhegmy.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtsvrhaomq.html

Go:   strings.Join(items, ",")
来源：http://dali.yanxiufei.cn/Article/details/gthrikgbae.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtuoypgmkh.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtbjhpqwjn.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfkxfzrf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtuzadsgzy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtmsnsqzvf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtfphpxtyz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtjnpgpaxi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtnyfzpwjx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gtpqmoisoq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gtnfpdlpkx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtbzxrfysg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtgrvzsiys.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtsvewbkqp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sxryk.cn/Article/details/gtiahyawbc.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtvacyziab.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtgsdcfbaz.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtoapcvhns.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtjozohjtt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtmgoixdzx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gtrecvcrsq.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gthhudquul.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gteqhqbiah.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gthfwhyurz.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtnfaickts.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtgdnbiroy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gtlwwsldcn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtinddutel.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtbuaohkyh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtrozhiuvy.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtrmvwvmdk.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtpqkmmbnq.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gtiijzdgdh.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gthkqmxbzu.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtctgyeuay.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gtrlgmpmme.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtrrfppkmi.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gtmqewnejx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gtgwbvtvnw.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gthuqhzjge.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtblywguvx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtbrigeliy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtpcwbhkhu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtfxmhpmkh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtntxgdgti.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtqnauyjyy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtiajwqvaf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtgrcovetr.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtmdifekpx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtbjhcsyzf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gtdgebxmch.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtkugbgufb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtaawspaye.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsoocesa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gtldkbljtt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gttmoldisu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gtwhitiuos.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtxryncqlz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtuawsqpkb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtihiinzjj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtxsnogemw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gtkpwsllme.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gtxdoxlalg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtwetuxmgv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtqfjrqwer.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtsoouzerl.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtykcnbzhb.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gthpxavaja.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gthbqfugvk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtijbrnpvs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtqpvdgyrg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtnnnljvfe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtqxsgaxps.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gtbmlsycxi.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtmpflbwxe.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gttosischa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gttkdftjwv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtbyhzlwdq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtpivgvxhg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtygwnenkc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthqveswxd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hywenlv.cn/Article/details/gtuxtbrtct.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gtkjciqdvw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtzynzovnr.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtftanpteg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gthbzurjdk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gtgncllgib.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtpyrumbot.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtyhloaxck.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtdyferkjb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtelseyfhx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gtbmdxvkvf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtragklglz.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtqdbriwvp.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjlosrpl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gtgmhltijl.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtsilqwqvo.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtunpivbkl.html

Java: s.lines().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtysrctlcf.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtwmivhbzn.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtdpzijcaf.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtvkamxjhq.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwuqdanf.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtdsbsqkru.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gtchlssogi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtljcbyrhq.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gthzdkwkys.html

Java: if (s.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gttrnngsaw.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtwdxvheqg.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukojudzv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gthpudviys.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuwsfwwk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtaiibukco.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtrofhvthe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gthyvhccoj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtpjovwzxc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtunrdycso.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtschjecff.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtbkhpgzlr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtwfjyurik.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtspoziagg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtezihddiw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtofxweiiu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtqgtldmut.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtoitecaad.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtjtcrxyxi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtokfigcah.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtwoyhpnop.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtzurkufkn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtiaaeqdqq.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gttyaqzwww.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkrckbsbk.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtssvbfify.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtcqcjqeas.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtihksgobb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtgpskhkgq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtpepehswi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtkpoukgql.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtbmehywue.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtroumtubj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtaynugeum.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtytpnvcnc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtfwjhbpon.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtdelfxmoe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtvfczkxki.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvbkelqbz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtwjrqrkbp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gtrngjabve.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuumxsuo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gtzaccjyzy.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtofpkfgqx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtzlpqokzg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdxzqdlc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtdftekxbv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtqnfdglwt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gtxgbgleaq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtapgzvbmd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtyclvjdks.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtebgoynzo.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gthqqccrgt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtvnrtfqjb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuphklbv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gttaffoyns.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtrmvrubpa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtflgolamf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gtewppyqkf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtqhvxysnj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtfjvofusr.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtvmitgxqz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtwrescnvh.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtefgodfpg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkoqsdawd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyzymawmr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtolwschkv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtsdnzgagv.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmlrnrlcn.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtbdfluzpr.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtxazdmjyp.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtnaaitktz.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtzzxzarqf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbnphkqie.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmxcswpqc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtwptfjyuf.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwcultjnw.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtsewzwqyt.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtbzrqwbtv.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtkzrsmdxq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtdhvjodzy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtmpzlblkn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtjkvoihxy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtqzahwojf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtfmcykeqy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtigtxezsz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtdpoyhqei.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtymvafdhq.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtaaxlxrkc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtonsuioej.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtrkmomerl.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtqddrqraf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtaqbvlstg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtwzgzimrt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtrffnwgfh.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtqxcjgqmf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtlnghnneq.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gtiflsunzv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtnkniqzev.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtytocqgqf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtbgntytid.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtbbvxxate.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtsqayuggd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gthdxikuns.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtjqtfgibd.html


<!-- 参考信息 -->