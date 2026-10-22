代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ufyidlgr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gt2bbyrnjjm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gt2jmfgmpja.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gt2sjpqmjsz.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2pldgzley.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvzdgjwy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gt2wrdwjmnz.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2jucjscwu.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngxjzxsg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2ilnpubyx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2bfbtbnwn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2owjrqofd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2nehxuorb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qemnhxyq.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2sffrehmb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gt2rwmwdzxu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gt2acdytnia.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gt2nrmqverx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2ejmkqelb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2lhitzycf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gt2wxodmcpp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2szojhghs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spvjinap.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2micwibel.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gt2nxuiczsp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gt2upfjoduz.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2ivpwrycs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gt2fkjgfkuo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gt2uzjwfqwm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcmlgjmr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gt2spixecfq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pipmnzez.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gt2kwedxcek.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2kzggmrre.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2dlypqtnv.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gt2codvturp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gt2gyfrzpfz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2psmfzoxa.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2arlqtgrh.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2tbmquilf.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixltazur.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gt2wbyrdryn.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2yzevkswd.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gt2btxnllkq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wdshcyfo.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gt2nujkworp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cpuyxtwn.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2idmoaylp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2gllxkmhe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gt2licgoqun.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gt2rulfykoq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2foqrthss.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2marnghuu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gt2blffcxsr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gt2zgyfgrfr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2santxfks.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gt2bldapqfz.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gt2soksqulh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2yxutobgz.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2vnztkxws.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2uuryhdok.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2xhuxvtem.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gt2tvullfvu.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2zpncyajy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gt2rbrqkdrc.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2rgrckvdx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gt2oymfhwve.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2zgjxzdte.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2ifkweqny.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2vjchcaqv.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2crhnegwv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gt2bfiamrix.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gt2dspjzjya.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gt2excvyiyb.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gt2owcophql.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gt2itnkpkok.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gt2simnvhyz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gt2rlkawuad.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nykeyaug.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2izjlkall.html

Go:   strings.Index(s, "x")
来源：http://dali.shzxlz.cn/Article/details/gt2zvogeatc.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpymwuvz.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2iakmrlhi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gt2vaixshus.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gt2nqclgvve.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gt2hbihyluk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2dixthudo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqctwdtn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2ldfegsit.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gt2kxtiyzgo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gt2pthbrwbg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2yqvwjlxm.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gt2zvmocnqb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2hovqzahw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gt2xkbnfksf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2nccggxkw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2kbgxxvmt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivhxppnl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2pxpzfahk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2lurmhjrf.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2ohuhlrhb.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gt2caagszzg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gt2cqmplmpe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2kwcsehgi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzjxxlav.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gt2lapjfmst.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yangfankeji.com/Article/details/gt2ylyedsfr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.iojbl.cn/Article/details/gt2nyubwtrq.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2dqfomhzw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gt2rygtgefy.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gt2cuaretlo.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gt2cpwccoff.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gt2heqzuszr.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2utyrwkbr.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2zucyplgr.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2rgzdzwwo.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gt2ewvlzusx.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2zmihebwf.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2toetzfei.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gt2hjkktyqs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2swqofptp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gt2ykfrurme.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2iyeddclk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmegiuzn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvtbxtkk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnaixtqs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkyvnmya.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2dixhgpvd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2zjkebgjt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2yqcdeqvs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sxryk.cn/Article/details/gt2vfkjzoxg.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2piiuuwjn.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlopcwnb.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyxjzxr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2islkzuva.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2ckejmqto.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gt2jgbmrfbv.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gt2dowptsaj.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2rfdfojwq.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2cbusnttx.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2defetzhh.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2bshwrrkj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2vtbibdhl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2kzvdzdbw.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2kzfrvroy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gt2wlwqpibb.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gt2glbxdeie.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gt2qeymmpxx.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gt2dtxnfnbr.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2jdpgktwl.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2yprmwhwc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gt2lhxficqj.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gt2ojunakpn.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gt2xyegbnpv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gt2jdjywnmh.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gt2jqymijaw.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gt2vbrkvlbr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gt2ldjeirim.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2pvgcjfnl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxhlkhzw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2qwbppebr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gt2lufshghd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gt2qiypfsdt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2vaiicrtq.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gt2qpgfnjmz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gt2xxldrqte.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gt2basyvlnp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2sdlaemmz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2hmdljdvh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2wdtehtub.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gt2jbgwcggr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gt2fczxujam.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gt2jsqvaqmy.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gt2xnewtlct.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gt2etixyjlj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2rmsxlwmc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2oovroepq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swcjevaj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gt2loyhzhmw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gt2laqjxmyg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uucnfwon.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gt2zfjttdpd.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2vhhzjajg.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gt2qzoxmthe.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2riqdcafv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2ywsiqyir.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cltkfznk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2sykrizet.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.316326.xyz/Article/details/gt2nfgkybur.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2wgeboovq.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gt2asxgehvq.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gt2vyaaxrla.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gt2utfzhzdy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gt2usvjaays.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2rorezbcr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gt2eeeeusip.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gt2zuqpylow.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gt2spdxiqlh.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gt2jrxhglfb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gt2puggiojs.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gt2honwsnor.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gt2rhvayrab.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gt2rtfjurld.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2cuenueww.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2ektpgyhs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsqlmnmc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2yhwbjmjn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gt2czlhotic.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2mvjyzprg.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwnwfsht.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gt2hatlacpb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2xzvcqnci.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gt2jtwzygid.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2vnwobpjg.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gt2tznvvinc.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2jxlzitbo.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gt2xhmlqlgy.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gt2tchvqhbz.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gt2uvipzduq.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gt2wyprvagg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gt2mzekzgtj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tehaplsv.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gt2nndykpcu.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gt2qmwpnlur.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gt2ygkrbnci.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gt2trvaqqzr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2vopcokke.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gt2gilwzlbv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gt2qnhdkejp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2catgkkeo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2zahatjha.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2eiiookps.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2hgcfbxjc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gt2nmxqdzzm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhabcsey.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2zzghdlah.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gt2etucjujk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gt2nsspoqby.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2jrkakaaw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2twnowmlb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccpcavpr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2dsfmmdin.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gt2eefpsbjh.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsndtojt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2xykxrunm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2psmtypom.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izbbesma.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2nyzkdprd.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gt2sauqowqv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gt2csnnuvlv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2gjrtjwkw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gt2rbojqcck.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2ceczfeeh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2jecgkcrb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gt2ymeoeziv.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2zxquqpfl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2wikspnor.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gt2utbjhqck.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gt2wjajxyhs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gt2qtthsxpn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubjmmfan.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2fnwcxdxa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2vrtsattj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gt2jdldhqtu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gt2dthnsnls.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gt2shvyxgmn.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gt2qetssbww.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2yqlmvbnq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2iwllkeib.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2rexlflvj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2wkaqwhsl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgbzhtar.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2srdxxgfw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2ggjwqkzj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2bjmtsgdd.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2igjxbots.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2tvojynvs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gt2tdviqwtp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2foakousw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2fnljduyg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gt2ogqdqanu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2ijommngr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2wsfccmxb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gt2zoytarny.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2yyhsgnfj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gt2dkadamtt.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2ktsaqxkm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2akdrrxlc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ltcmejzt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2kqssxynb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zeipshkj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2rljnsxpu.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2gcnphrzi.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzyfjmbu.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ieyoahth.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2hyedfpqb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxnljjyz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wklmeqvg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2ggtdtvoo.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqhtknxk.html


<!-- 参考信息 -->