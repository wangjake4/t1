代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqqiwqib.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gt2ckiygtfw.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gt2kwqcafgg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2ngkjsjhq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwgdbqyt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gt2bipkbfnr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmtictkp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2uzhocilo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gt2gntjygcq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwmsjdag.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2izfutiil.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2vjryzvpb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2etifwsmm.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gt2rubdxmzh.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjwgzpow.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2gweniqgo.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2wkqvhyxb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gt2upiitpgf.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2xuieemka.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gt2kwpbtfoz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2nwldhmuw.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gt2nxwxdbfq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2cbbqbqma.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2cjeonglu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2oearwsrm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gt2liieppaq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2wzwbqzgm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2vqdsngvf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gt2voeyijcu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gt2jaiipgql.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gt2zfkdhrsz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2rzhvsyib.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gt2atbmpaee.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujfkymcl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gt2xxesthzb.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nehgzpyl.html

TS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtjubahe.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2xiekjxbn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjrporcz.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gt2ylnqpclm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gt2jxrxjnjj.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2wqklohto.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gt2yjembxdn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2anbvqjjf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2pobeynso.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2lmhjxxul.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfliazyq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2nhtcepkj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gt2sgrsoccn.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjsmqsx.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gt2nnleemtd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gt2zisdewto.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gt2afvogptm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gt2qwfyorka.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2tdklchkz.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2otsxjwyh.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gt2rxlficcm.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gt2audmytst.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2zavcoiyk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gt2bhvjeszh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2chzaoxeq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gt2mkupgkse.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owxqpfyq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gt2zzztzdlw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkcmhlab.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gt2rdmixuav.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gt2qigsstgg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpekhnoe.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gt2bcwtbtfd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2fkbrrbfs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gt2qerdazjh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2dfjufaiv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2counsekc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2nwcwpifd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2bqpoeqhj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2fmsklgii.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2dipviqaf.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2qfomaufb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlzomctv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2timhxaeq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gt2cgfxgqto.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gt2vxevhatg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gt2gddcmubh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gt2pcbsbxqk.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gt2vqmthvkp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gt2cabelwto.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykksxspg.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gt2rbnhxbjz.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gt2upjaxtqd.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2wofbmtxw.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eurlhdln.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gt2rkbejoyr.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gt2mnusxfyh.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2duolqxgi.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2mepfkhfi.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2giwzmhpf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ivvv.top/Article/details/gt2wkjtpksz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2nzktwxxp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2fxpkbdun.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2clgpfcwy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2bzdvfvhg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gt2uljaonkb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2fcezgrwi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gt2tstmpowj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2rgnjmmgt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gt2xstautjv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2demxsmxa.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2rmgkemjy.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2jrjndjwr.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2xfqptasg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2ergbzsro.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2rmkfjicg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gt2cxpdzqge.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2frnwmuyw.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfptcicm.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2hphlwxcw.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2bwjcdvfu.html

TS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2iazfkckn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gt2gtwayres.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gt2jwtsoclo.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gt2yqoiwpcn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2hrghaosa.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gt2dmzbcove.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2byvcdhbw.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gt2qumvjotu.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huxfmequ.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2fxblbzmx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2btpbfjvp.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gt2xxzzaslm.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2iyqatyph.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2xgkmtsob.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2upfmteyz.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2lbmeauxq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gt2tsxwipjs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2fqkcqrie.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2vjrvawvm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gt2dcmrbkof.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdxakprk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gt2dpbymfnv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2gndfzkcm.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gt2eyqclvph.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gt2keudhbgg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gt2cxsktlpu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gt2ckzohels.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gt2lirccmae.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxvbztbz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2teztyadc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gt2hygrixxk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gt2ontalaht.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gt2qudlknuj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gt2cxeomfsy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gt2yyjqghsi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gt2nsgnyxkf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gt2hcfgzoec.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gt2symilnhg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ozgkwvpj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2vhigkpff.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gt2whogktaf.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gt2qyuztvrk.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2nnfkbopr.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gt2gemnqzhg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2wrmwqlnt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcgbghmj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gt2ztdfvheo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gt2dmfsersj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2loeknmzr.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gt2jrawrtfl.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gt2kwaxntts.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2icxcpswk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2xgwtqpta.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gt2hulpomhr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2tboktgfa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gt2quhkrtls.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gt2hhxjtaxg.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txcdpphi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gt2wahfprxy.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gt2lextvhuz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gt2qhtzwxug.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gt2tsiressz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rabxpobl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bengeyqj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2agyleumq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2fsxrtwde.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gt2bjllcjnf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gt2mtuqinvv.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gt2xnzrdhsb.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddjdtstq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2dphrcrxx.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gt2uyfbwxxk.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2nnhfevji.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2afirgmer.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gt2siejpvxk.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gt2ojaqeaoz.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adztwfxx.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gt2lvdzrofm.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gt2xznoqyft.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gt2mwoyuhru.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gt2zencmyfv.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gt2ogosrflk.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2lvkexhdd.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gt2zygzyhbv.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gt2fxygluhg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2yamifbkx.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gt2ypzphdne.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gt2ciuggmvh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbkoflww.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2eoakbugp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrxvrmqh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2fvhqrnho.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gt2mtrkgvwk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2izcmvwve.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2ftaadkwy.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gt2qzukzxwr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2tmdwmhgp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2hcqewvrn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2vzimmkyk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2stnmuxhx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2uaketcjw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gt2aouurgpk.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2tbmrqnuj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2ruwrxjrz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2lwbtstxy.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gt2zngcjmeu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2bbsajqll.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gt2atgtcclu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gt2pkqxjdrx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbvpwfte.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbhqamxu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2cnvikncu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2swfmjdsb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gt2vuvxxecw.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2omwajrnq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2zqokbzja.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2roindajn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gt2osopgfkp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2gnkfokbx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2bomxrjgo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gt2rdegdflj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2wegujbty.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gt2kzsjcshp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmxzyfhj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2ggduaimy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmlhlgqw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gt2dvcavept.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2niyejtxg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2aqosfjwm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2hemsnfzo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2kazwkhbn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2csrtrzsb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gt2ajzvmvnz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2kphxtwui.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gt2tfvkohrz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2pqfkmptf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gt2ubquvwlx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2rynfracw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwvoggct.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gt2maokctji.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2ydzqwmdx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gt2mkzumxgh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gt2ioonexvy.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gt2jwtnffuv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gt2vmqjjgbj.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2tftuowij.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2galskcui.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2mcechmjb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2dopsttqa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gt2bjsdhovd.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2ewumckmx.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pygsmjtd.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdejlwpp.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2otzmrvlf.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2tdbsudow.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwfbffpp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2gehmjjse.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2fnimghuk.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2jjdrhlyw.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2phrfivuw.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2tspmpzze.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gt2vrrfqboz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gt2kncbobuq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gt2xynvyeuh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2fmbvrbgf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2yfeawbxl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gt2sfjsvyvi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gt2eflcwpcr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gt2diwvbznc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gt2cmbhueyh.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gt2ddaipxud.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gt2cukjurzl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfgruhaw.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2xaregeqn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaucysej.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2udilqqqb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2fwadmddr.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2ydqcwmtd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gt2plhodllk.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gt2ygsdkpkl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2bxdxpxym.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2jsngtvtb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqeuotfq.html


<!-- 参考信息 -->