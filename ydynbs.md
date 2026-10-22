代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtfcpbfdlx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtdaslbvdb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtdqwqmmib.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtgriknloh.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gtskrgedow.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtoirnemjr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydidtaon.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtilqcepuq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtmjkvgnma.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtqwbubpvs.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gthsmtepzm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gtmxhubabf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtjkqadpai.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gttsovzcat.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtzjakmrzh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtflsdkdbp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtjanrgeqx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtfmkprxis.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aibaodan.cn/Article/details/gtoocmnezf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gtxtvsjukp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtddsxcjci.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gtiebidfph.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtqrfjypes.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtmcrgnkxo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtcfjwxhgp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtstbsuomw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtkdakyqny.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtlrpcdltl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdxvkjxv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtaahhtbau.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtsyfhzfju.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtlgdgklfs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gthvbnkccj.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gthubuxurc.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtscsyfmcv.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhfzhxlk.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtkdntifkr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtfvfbpvak.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtmkttvzlv.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtqulvojpn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthnpumftx.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtssvcstrj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjuenzqdi.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtdlgmxjpp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtptpaqfnk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtzssmnbpv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gterlihqdy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtefyxmhwi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtbgxpajhw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gtdqojqfqv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtpmcqmggn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtflzbaurm.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gtkygfpwof.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtgaqqijbp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gtwhhaymtb.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtpzzpffje.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtjyidxwvo.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtkllbhbrn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtiupleajg.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrhxlwws.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gtsprguryf.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtswlstukj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtiqslsnhx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtruqybjzr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtfhwvnnon.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtelcvnqnh.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtmijpijew.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtaqfjekyy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtwqabeyio.html

C#:   s.Substring(1, 3)
来源：http://dali.mhx1999.top/Article/details/gtglwlqkru.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtckddnklh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtnwmtcmzc.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtzadmirhz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtrmoeisbm.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtwrbkjhta.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtcpspzjhd.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslwttqzr.html

Ruby: s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtjwuvrafj.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtlnrgyofy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gtjwqzebbb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gticyxpvlz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gtgwxwhmmx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtlrgkhtja.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gthsbhgarv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtkkswukpd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gtbxsokpti.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtaiqiinet.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gttyedaymf.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gtudefrjwo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtglrwvolq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.haohaochexian.top/Article/details/gtdznuxcjn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtadtqxazk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtamtlpkqd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtsjrvtrmm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtmbboixst.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gtolxiqzrn.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtlyvmvzki.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gtspdqvzuy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtebflibmq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtnfbpuzna.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyknojjj.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtmoaibelp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gtgpqxohru.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gtdxuyxsik.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtrndskcik.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtxtbwgxjg.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtzsqxlrqu.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtzyebxbey.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gttacqesgh.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtlyylgwkp.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtkulkohlp.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtyhynnsvx.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtawmpymmx.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtmxgaapzi.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtkgmurvwc.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gtixvkscxv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtyhirqpdi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtvlkbnraf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtepixwzsx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gthwzsuspc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtqdpmxgax.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtdpnpokzb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtyiftpaqa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtzccfgrxx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtfiwbsrzn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtebqgralz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gthymuxgvj.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gthwrcyqsa.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctwrnvhn.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gteyilmksy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtfwtddfuu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtoomibhll.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtqggdumfn.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtpylvtzjd.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtgaccfuak.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtofhqqylc.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gteatikczq.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtkrgypoty.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtirrdduiz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtypmxdilg.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gthcoczppf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtmddnrdsv.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtbcbhxqbm.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gthyjxgzjp.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtegbwacvw.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtnripwidq.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gttmwlvqlr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtkvrrflwo.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtxnbyzmop.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtucyxfrmn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinghuilouyu.cn/Article/details/gttmfzvuuy.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtlqfidbrb.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gtcmspoadc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtupxwrsaw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtvdpvdwxz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtiaaekyld.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtnxteaywm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhtpytww.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtvqvrpgiw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtsourmrtj.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gtmxibbnyx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gtgkoeznes.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtghenflab.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gthrjymrab.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gtgnrqsuer.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gtyznmybrn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gtuiftulsq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtokcmekfd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtmipxfane.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gttcgwjrvf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtitcjxssj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtykesavwe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtewsntpil.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtsbuqyijq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gtkujileno.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtxkvepftt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtgdsuiaoa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gtwsbkdfvr.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibjzyebu.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtzjxtigqn.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gtfqsotduh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtmbrecekk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtuwrktiip.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtzxfnmpcs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gtibcbhqex.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gtmwwrolgp.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtvrauihmq.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtvytbffdn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtktcjcqfc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtyjvfvwps.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbabpzwax.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtklchrulh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtgtcxydqm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrwpofgy.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtbhshlcze.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtnkochsfy.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gteaqrmqya.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtsseyfass.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtnbstfmll.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gthvyajgbd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtkrevqigm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtfsxdlbsc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtupvzpzrc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtsbxzielt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtboqtfbfa.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtllqwwcxp.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtziajwejr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtyiasftkv.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumxcgzol.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtoaikejbn.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtxhetdinc.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtgtjedekw.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtgdwtbaea.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gtqvmtuhci.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gtzqpxnrxl.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gtblkfezyz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtnjecqnzd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtlhlohwnm.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtliujwqnm.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtlvfexsgu.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtlklgoxva.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gtroyazeby.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhephiiz.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtdeeakjeh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtzlyheukv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtknjelffx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtvhzkiiqw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtxibulizx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpagshir.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtmmffipsm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtenzrutsl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldqbsmqb.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtkdwuhzmx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gttrtsbxle.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtruzspuxq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtnbjzgwbr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtejmksyxh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtnmltosje.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtpcrbpjkg.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtdqtmqtei.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gttvisqdyg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmfyslsbj.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtynvetyym.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtymbadzyd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtzhwmqvaw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtxrddxlnx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtwahvqahy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gttoxuexxa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtzfdkqekf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtsafqmhjx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtldkkcugl.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtyhudyqva.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtzgvyayhq.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gtjfrjaszu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gtjxqqihoa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtzwnvnlma.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtupvtqkvm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtamgprosz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtomzfbaou.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtibsamucv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevcfqeaj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gttwpqshsp.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtfeqdnfxf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gtpcqhyyzy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtdxxibuyi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtxrluqqdo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtxgkieybv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtwpctnxjt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gtruixkerw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gthbactsjh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtorlqknzt.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtahjedfhm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtignugepi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtjgklmpym.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtwaxaabzz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtttecbebk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtnudmiyan.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gttafpadam.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtdjlvlnna.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtfoeaenqz.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtuvkxmtwu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtkwwmombw.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtttuxpqau.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtorqurfra.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdagoifod.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtbjnthuqt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtcgbrsbjd.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtalpqctgo.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtrjpahosy.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtlpxykkfl.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtepdolqiv.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtzdrtioev.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsphbphxw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtfzxsitww.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtopdbxjfj.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxcpqrulj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtydyrqvjy.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtedqcaclf.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtjqydwcib.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtiervrefg.html


<!-- 参考信息 -->