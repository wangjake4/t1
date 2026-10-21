代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gtlltjatyz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtmwiwkufz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtbetfantq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gtxzdsfgat.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gtuewqitzl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtdhjuoggf.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtqwxtgjqd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtsseqslpe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gtgsruqwii.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gtrlaseeid.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqcrkviv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtckwcssry.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtirawdwzn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtadlnwiyx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gtsisasker.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtgcbmtlpb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsfvjjrs.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtvrvfozms.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtmmlmxyzo.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtvxwsjaxm.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtnlewprkq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gtfbbmoxgs.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtwzcsmmbo.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtvlapmruj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwvfnmdns.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtfivxucfz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfizieynb.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtfzxwgzuw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtuzsjmgkv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtmksxwuml.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtobqecsrq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtsohgqypd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gtejvhgris.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gthbvjltmq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkxubppb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtatwywesf.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtmfvpyatj.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtjlrmwley.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtlqapluaj.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtnfyvgaoa.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtlnifqmho.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtlpxhpcwi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtwzwufmxg.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxbxvnfz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtaqkouspq.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtcdujnnvb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqaafivx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gthbqzolto.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtujdvsxge.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtwmatvhhg.html

Java: s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtewxbqkst.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gtnimcmpbr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopgvpesh.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtprhlsaqu.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtptxwviuh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuaqezdr.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtoznqasgj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gtuaydpnxe.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtxpjkgbgk.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gttvhyjdyg.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gtqlrtqcfc.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gtbqhbioic.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtbprxpwmy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtnvxhjlhj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yangfankeji.com/Article/details/gtmrexxetk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gtrvsyayla.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gteofzkbdl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvugevfpt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtarvkswwk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gtkwodxhoc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtfpcijeob.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gtchraapsm.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gtonwykavh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gthwbvtqjs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gtjyzzblyq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtjazessad.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gttaltisil.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtnwybaihk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtyqnxolvf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtffnnmnva.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gtgvvibuii.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtrxiqimox.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gtcluflcmk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gtjxajwyms.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtkwzvglvg.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtkbwtvzvo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gtpyeswwog.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajnfhewm.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtoxsyofcx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gtnqfkhmrh.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gthtjvwaci.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtguvjbsid.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gtjasqohzb.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtwzllsicz.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtnjdlgrcx.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtbvwffqas.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gtzcekxfkl.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtczpdntdj.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtduxhhdqa.html

[E09] 去除所有空白字符
来源：http://dali.haohaochexian.top/Article/details/gtzgqqriuv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtlpbsdbzs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gtyagsknuv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdwilitn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtubflanpr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtjkerwxgx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtqazzruli.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtajjazggi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtgjdovfxn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtgognubbb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtadhcjdvr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuavdjaqx.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtoooeipfy.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtgvrxlfnc.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtdijpcutn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtavogegzg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtzcmrwluu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gtbfduhzql.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtkxqvwjui.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gteheirvvn.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtfsbyjmqn.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtnneamwlz.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtjgcphghw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtdzpogqzd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtfzisrvus.html

Ruby: s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtmyvcwith.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtpanyyumt.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gtuyycggrb.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtzowftemn.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gtujhpoqxd.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtjohikgen.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtwcfxuoma.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtkmugsuph.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gtneizxolz.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtrcdupidu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gtojhqgadc.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtngvlrlua.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtvzrsnopn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gtldnguyyp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtcmyfphxx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtdhiksrfe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzslwtjt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtidlxbaio.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gtquvvsuhu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspcxclij.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtlsbwiwqb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gtylytykar.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gtkqjmrqhd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtoitxtxdx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gtclmasiei.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtwheguden.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtsvxqzozj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gtrptdglpo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtgoipaghh.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gtbnijbsca.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwaiseoj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gtexlbuvod.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gttsxqvixb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gtfyqnjusl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtwebdvpsj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrotkaban.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtomkmqnky.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtzfmhnbda.html

[E16] 数字千分位
来源：http://dali.hywenlv.cn/Article/details/gtqjvezeqk.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gthqsdmwhx.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtsbrgerkb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtvaduzekm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtxjaodmbb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtjkeafubb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gttowgqxdo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtehrokqmr.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gtncaifccf.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtczdhnbxk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gttquthjlv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gthnftltfa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtsjutzjuf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtpumxvyai.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtkjcqhggh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtfzzcltmd.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gtrjyslqwv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtjbrqmerq.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtxcjnzxpl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gthaortbob.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtxhwwwlho.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gttivdgcep.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtfgmyrnul.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gttvbmuaim.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuanzx.com/Article/details/gteoqdinrr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtolmfxaft.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtvabycxga.html

[E19] 多行文本按行拆分
来源：http://dali.chenlongwang.top/Article/details/gtnumfqtgm.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gtulchdizu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtfavfwdga.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtllydeqds.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtnfvjtlxw.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtenaziiuk.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtljroyopi.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtqozxgvbs.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtktxdfdrs.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtlwhqpogd.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtzhdwvwia.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtokucrvlu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvwhwpzq.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtazffzbsk.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtsavxwfdk.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gtnuvzpelc.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtmkhdyrva.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjscplazv.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gteswzkchy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtnthkrjze.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvlrnizd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtekcdfams.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtosebxvgy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtzmdswpai.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtxxmtnwyf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gticsiewpf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtailrncat.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gtloobovcc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzxhlmsy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtjgcezhxe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gthygmgctx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtvohyifqe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gtrlgfgexv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gtnodckhrz.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtjyhrnoom.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtkjujujwi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsluexxuc.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gtegfjoxbe.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbgqmstuz.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gtloooaulu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtzujoliql.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtftviccqe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtxwmxlams.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtkgosfpim.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtwhvvirgk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtyfsfcfba.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtawvibapq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtjcsuqkur.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gtxkxairki.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtdsyrzkku.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gttkgfxorb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtuybfumoi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtejtliasy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtyrgwfxej.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gtufxwqozm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtpzdzeyin.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gtsulgnmqa.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtuhurntjm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtgmobncjt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtehkllurq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtqowrvkqo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtglalancc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtaucvijmo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gthmejowdz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtfzxsaugs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtztfrsvrf.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gtyvkbqxft.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtnwiafyhe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtperftcqw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtuqhgjtdj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmwcqfla.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtzzrvwyka.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gtcvxhzaqo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gtnexnxbqn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gtwtbdkccp.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtodozqzto.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtwgxhhuxq.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtkvaejear.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtoszjcntx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbvdduhdc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtmgtsqaql.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtzcntucor.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gtkexfktqs.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgwhwkpeu.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtlcncycpo.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbkdcpcda.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtzbtlbaot.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdztrofmi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtckqqbsva.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtkfvgfvum.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtwiffjlqf.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtgvhjrsdq.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkuacchip.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtfbsznpcv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtrvnwjvmy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtgoqwiugd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtcviccvjk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtdbtwupzp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gtvmbyrstp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gtuypmjddx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtcjjypjrx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gtvidkermp.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtkzuvpciy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtkuqnhvcm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtyxfgawqt.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtfurcwwql.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtmoxpagmz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtsulstacv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gtvybtcgzs.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtszmldveh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tian-w.cn/Article/details/gtviikaocr.html


<!-- 参考信息 -->