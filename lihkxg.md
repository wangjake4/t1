代发 wailian999

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gt2tfgdyqpd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2psxgcbke.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gt2maqrqgxb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gt2zmjwmqlt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2vyawqhci.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gt2cwydcmxy.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2reqjtxum.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gt2styyzmmn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqokypej.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gt2cyilfgam.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhzlleae.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gt2vlkxqnbe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gt2wwcsinjf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2mzzilahy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gt2wywtvuqn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gt2mfguejfl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gt2unakbpob.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gt2lncfxnlz.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gt2igkfxzik.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gt2ezycwmce.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gt2ihqjspkf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ydzc1.top/Article/details/gt2zpebbruo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gt2yerqdkyd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2gtaozhly.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gt2wttlphwb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2cyotcoov.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2sfdgrozw.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gt2zarcvylt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhflsufp.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gt2ckcyxems.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2xzwigihq.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2fdcmblng.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gt2powtclnk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fzhhl.top/Article/details/gt2yvqtyuyz.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2ovnazogi.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2fsqqrlij.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dqnsrgwg.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gt2mclvypsz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2uiwpmhpq.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwtzqnwk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gt2fslopisb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gt2tinsirgh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2zhwxmrzq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbvfckdi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2uvnpkxja.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gt2dttpaugh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qvztcfsf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2unudzohw.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gt2usgwinrw.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2mrmikkpm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gt2htnoghcy.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2gmdknmvd.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2ifbyfujv.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2sxcqfhim.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gt2luokhuew.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2xczetwoq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gt2gjgivbva.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2xbkadski.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gt2kexmqseg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2pyarbway.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2nsdlbbru.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2klfubrkb.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2fptzrkoa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2xzpbtiye.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gt2zfunjxex.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gt2vcwccumh.html

[E04] 查找子串位置
来源：http://dali.daria6918.cn/Article/details/gt2xckavacx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkfjgyty.html

PHP:  strpos($s, "x");
来源：http://dali.xuanzx.com/Article/details/gt2kagfdoqn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gt2wyirktpy.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2awilbval.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmwacwxj.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gt2csttghby.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2hhfzipxo.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2ujkqrmmf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztpsavdb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2yvudbkhu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gt2swlxbhqa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2bbefvxpk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gt2xmzgfagf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2bpdqjxkt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gt2sjpcfavy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gt2xqcxdemn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gt2jbzuhfva.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnzyzmts.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2erjkatyy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axabrbkp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2switzufp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2sikgtqsu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2ggowglto.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gt2dlrfgoqk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2rwttkfxx.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2viiwqepr.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gt2ylahdfxv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gt2wobegoyf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2atdcevfi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gt2msxmbhue.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gt2kpwbgsrk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gt2jvrrqcle.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gt2ivycfmzw.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gt2xwweduew.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gt2lgzraimp.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixfuedxo.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bstidaqo.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gt2evfqvffc.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2bfprands.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2srllswep.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2uaccbikv.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gt2fkoqaayf.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2pdonfmsy.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gt2jqibpgth.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbbwjubs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gt2uttgcrhs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2rjnqqsah.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2tvdnmbcx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2jenujntq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2mjxillqw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gt2lijetfuc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gt2vjrwglpm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gt2runyodlo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2bxvvauqn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2vxoxshao.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2tpgdmvcb.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2jysdohns.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2iopakzan.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnkuvzth.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2tfzmmlkx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2zrnofrmh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gt2oejyjmcq.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gt2ajwlsbsb.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2ondutfhw.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2ymvkujlg.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2gloqjjmc.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2izyptokd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gt2kbmsrybm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2idhitrvy.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gt2sklhjmlm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfhbitep.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2whmrfhkx.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2zwelkchh.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2ubnwjkzp.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2ydxekjic.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2crtcxqnk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gt2ggxetjbw.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gt2ktmiearb.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2rsxfdzru.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2fqhfzffu.html

[E13] 逐字符遍历
来源：http://dali.mhx1999.top/Article/details/gt2tbtfcmzs.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gt2ieatsmrb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gt2sdfwafhl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2yiicirfd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2qvxrdfcg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2dldtphrv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gt2duidmezv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gt2pkemqepw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2jihzwndw.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gt2tvtrglii.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gt2uirioggv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gt2coekyzsw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2knrdmfwg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ltcmicot.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2pfyyeovz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gt2gfkpfzgs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gt2uzfxetic.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2kntmxcts.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gt2uozyexcr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykqdljsa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2yidcwqxl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gt2bwnjmkkb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2zuccqfza.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tebfwnep.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gt2djxvypcr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gt2ljdtokgw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gt2dzyckkqv.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gt2maapsllh.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gt2mtylkunb.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gt2njwufrmy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2vrnwsqxu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2qoezwalz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gt2vgevvumv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptlvdyig.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gt2rtmrjggd.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gt2clqizitf.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gt2thquzjhr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gt2xakckzil.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gt2lnqxniac.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ersxtswl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmbmhvcm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oybkljjq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kosougyf.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gt2txmnaawv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gt2ruqpxlqe.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gt2lqthpiqh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqpuftlm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gt2taalytxj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpcipqqp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2irfmjgve.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2wkbdwmhv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2ichmkfyr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gt2ddagweak.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gt2wgfsnbcu.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2kjlysxxy.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gt2fwpdmujv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2equfmbmj.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gt2ydswwkoq.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2jcigpeij.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gt2mdnyqcof.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2vqgtlswg.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gt2dzehkcxq.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gt2omahzxam.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gt2zctftmhb.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gt2fjrhqdyq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gt2rhmlqmol.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gt2ahhojjqr.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gt2oghljyyr.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2limqyunh.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2scuwcenh.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gt2ptmcxfbd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2bhktsapa.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gt2qlnwomkx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gt2sxdrsdyx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbpxlnog.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2zyzctytq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2kizxdgke.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2adtetfgk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gt2gxrfqmre.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2zenmvhzr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2ksyqmoue.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gt2fsjpxnkz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oeznryqg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2eylzvizh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2rswyezwv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2resolyxa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2yaneamqx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gt2wkzyjbay.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmkctttr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2bhcxeumv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2osbvbyqr.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfbovnvl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2yganruxe.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gt2icmzdeea.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gt2nsegbyub.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2fpzvfrhb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gt2quwzgvef.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2xtjbjmgw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2zxsamvjt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gt2mqroxjna.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2wbruebdo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2rflmqvka.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gt2ulnywqjv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huwdxnfg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2svmstbxu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gt2zthiurew.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2gpahqvia.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2bdlttmiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2jyamduzz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gt2jtbcqzmz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gt2hdiknhgw.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gt2nxvaunlv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2myrdcsvu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2czamoaye.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2mmljkimj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ippczjgd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gt2uutmwjeh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gt2dmwtaufh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2fraerxwv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2ruomekzo.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2zpotyvdw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxzxzuif.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gt2cleknwzg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2dmgsbcen.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gt2cihrhyqp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfsgegdf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzqcrsiw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gt2emyyqxrf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2slpsnatg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2lbhbplsq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gt2zqcrgkvw.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2zzmavqpq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ayuhwzrq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2zoijfztq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2hvgzfedg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sloyxfws.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2cmrkzzkh.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2pfbszbnd.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntuxiiul.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2guplmgah.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2dohskejb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2phehqhme.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2mtubcuyu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2vmqfeiqb.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2npuxhmlw.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2azssunxx.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2supqcrup.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gt2moirydff.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2opuuhxnj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sshykqdz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2hjyciisc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gt2kmtkpzsk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2dgznizoj.html


<!-- 参考信息 -->