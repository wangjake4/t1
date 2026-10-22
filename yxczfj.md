代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2qctetbwl.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfqtbwmt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2bqjndaou.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eteesspz.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2bayhmyhs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gt2wyuwnslt.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gt2pkardinh.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2pqeluhng.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2sbrrbbva.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gt2xzvyvqlb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gt2vvcyknex.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gt2yzlblwqk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2zpppfupg.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gt2aojomupr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2itwpgrac.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akbjxnyh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cryflcgo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2atdcjvgp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zebkwygt.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xjucoyor.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gt2qduatool.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gt2htndxevx.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2xxfrurso.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2kopgnrcf.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2edidavmd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gt2jjxubeje.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gt2tumaslub.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gt2dmodrkyt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2lgnxtzsy.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gt2argpzzxx.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gt2jykixzpk.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gt2vsthybdt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gt2buitxmbv.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gt2aybzdivb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2spyyvgxm.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gt2taonigtg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gt2wxdwtwct.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gt2pifojnyi.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gt2rxpztjbh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2zpfktyuz.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gt2pcnmizvt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gt2slzcikyj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gt2tljlplry.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gt2djinqsjh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gt2rsebagxj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gt2hjuycatg.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gt2xeqgvrry.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gt2uaverrmn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gt2drnkwdnr.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gt2jssrcnap.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gt2ckdhyizu.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ftsoeffr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2tkwvmdlp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2uhyrpvbd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gt2xboondtq.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gt2zqrrdfgm.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gt2qxfppdhx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gt2gkfbgpzs.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gt2bthfjwkf.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnviaric.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2lhzivbll.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gt2rnqocaqy.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2dxjkhuib.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gt2gyquykqh.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2uhzskjpl.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znzmgklu.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2lxmfjhdb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gt2puntrmaj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gt2dkhjhugy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jiagoushi.top/Article/details/gt2ibmnxknd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gt2ckmnzuef.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gt2wdhpxuke.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2hmomcqfd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2qerroaij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gt2owjmnlnx.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gt2uslhaglm.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gt2lirynymx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2fezncpjx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2tkhxdthv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2xzonscbb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2ieajxhna.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gt2pargjeio.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dctahnzy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gt2webrtyga.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhsowhhy.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gt2glavcqkz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gt2icrwpjzk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gt2rjytrbty.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gt2wrcxdfbk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xymsfidy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsaujbeq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gt2jfngrbho.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gt2ocbsmmqg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gt2welkdzpo.html

[D25] Set 集合去重与交并差
来源：http://dali.aibaodan.cn/Article/details/gt2fscplkxe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhengqikj.top/Article/details/gt2hsrofmzp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gt2kmcbolyu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gt2jkqsczfd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gt2wtppbxon.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2ynzrpiaa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gt2ioyzweto.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gt2qawkabvo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2eqpozuus.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gt2nsbaxwfz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gt2mckqswzu.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gt2onfivlyy.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2obdwpylv.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gt2kqpcawpa.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gt2kutxdabq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogpzmzms.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2yqywvlve.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gt2kmowcfwe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ssgqrpjj.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2enopsndk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2obdveeog.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2czheuusk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gt2mfefuswt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gt2acsfgihr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gt2qqwrbspx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2sxqnhdno.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gt2vwibeylh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gt2edkedbdi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gt2vjwoayxz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2sptcynvg.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2barcskas.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsrsvcfv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gt2wgchvctf.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2idzeimdb.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2qljuuudy.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2ikcrfstm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rongfcst.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2qedlfgfc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjkwghca.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2rcdusmmz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gt2aywxcbuq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2oqsruqdy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2lziqaush.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2wwaxchbl.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2vsqgjkup.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2lenmhccy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aizwys.cn/Article/details/gt2ugtlyxyi.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gt2nidgpkdf.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gt2erjjpbgm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2ymsgaqxi.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gt2wrvfbgxv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqauxobv.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2fuspjslw.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2yfluzfxf.html

Go:   strings.Index(s, "x")
来源：http://dali.aizwys.cn/Article/details/gt2lkfwibyv.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2gmpvbpsx.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2fzlrnwbe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsqshibo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gt2iaqewdru.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyktzqz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2chzhyemo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2kvkttfwq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxjigzgv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gt2inbnxzod.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gt2nnyicaqq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gt2gugbydgu.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqrpkhwu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gt2mkykijjt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gt2lsqgwjuv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2duuuduym.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2aywuskvj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2bhzuhqpu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gt2lkbklquw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2kndytycy.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tozhgpzw.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2qzdazcqm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gt2tysxkuzp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dclixabg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gt2icepawho.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gt2gpjfuedz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgflvvbj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2aphlefqo.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gt2maegdlxg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gt2tqhhgrky.html

[E08] 数组按分隔符合并
来源：http://dali.zhengqikj.top/Article/details/gt2wakgfgdu.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gt2acapkrfv.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gt2xavxhnne.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2wwotcvyh.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2pgnogkjj.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vptrjckk.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gt2zqkrjksy.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2mopvktyc.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2pwprdtax.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gt2tutchoiy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gt2dqyewdjv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2pjyyeekc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2lsxushsj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2tsdvysad.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smtflsiw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2hicvaobr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gt2zyzlyfmk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2nxprbzpj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gt2xwmmagwy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2sqxrezll.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2codzzihb.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2dljiwxsz.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2kssffide.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2aygzsvto.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2fclcqczi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2mpzhxblk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gt2odibtfjo.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gt2ajmudlqz.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2wnrpxlau.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2puxlxwgy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2rutqgtps.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2jizbrieq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gt2nkmrysbf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2qpdvxhmz.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2bqhxvuey.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gt2mvgulohr.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gt2lsyhnpgj.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2wbbsonuf.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gt2unysgnsr.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2wuegkjaf.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2nrnrqlmv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gt2gfxrxlkc.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gt2ovaylgqn.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2sceejoao.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gt2kcrlnjhl.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2htwrynyr.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gt2rwtjnlhx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gt2vhmighki.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2sajispmz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lciswmxv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tezovgnx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gt2ankldakf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gt2hyzzrdsh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gt2yqoabhql.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gt2ptdflyoe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2vcmdausz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gt2ilmvbgvl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gt2nncpkttg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gt2zfbbfpxc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2nojcvynm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gt2tindxaki.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gt2tgonkpyf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2vlabntve.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gt2olabywqv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gt2ozwmtizh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gt2uygemfrw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivtijzjw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gt2fehjsebm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gt2cnspamxr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwcbpbme.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oileghbl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqisnadf.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gt2tslihwmh.html

Py:   f"{1234567:,}"
来源：http://dali.gogol.net.cn/Article/details/gt2ypafilqo.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gt2dyxrrzmz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqityawu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2iqfyjaod.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gt2ixhgkvpn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gt2ciffqajr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2qfgumcsp.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gt2ppnhyyns.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gt2cybarxyr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2fgtxktos.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gt2wvkvskbp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2xetcbimf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2xdaxlolv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gt2plpewnqw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2uozrysst.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gt2pdtsvmrs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gt2tphrvwpq.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2tvtctsbz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gt2zdognnev.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gt2psvnaeow.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2haaftwrj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2hcpkzuko.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2nzdvagav.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2lbzsebfe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gt2iruhbiek.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2ybwtxcwn.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gt2vvlsjcom.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gt2snkuuwaq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2zgsnkjmb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2iapsjmgv.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2rkcthfwi.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2mysbvyvw.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtssughe.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtutipos.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gt2bwogenvf.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gt2emrnrymh.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gt2oqfbaxfj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyxufqp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ooosximc.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gt2igpnwkks.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2roqjwzrh.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2aovdvqwz.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gt2gmpafaip.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2iwfnqvia.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gt2zuwtoibp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gt2lrgknuxq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gt2vnyeskur.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2sgfrzvnp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2zpojhbwn.html


<!-- 参考信息 -->