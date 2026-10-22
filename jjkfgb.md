代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2adotijnx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2iygfgjiy.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2zygiufuc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gt2zkteypnj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2ighrjkld.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2kppxawet.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvixeflh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gt2mpbpryis.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2lgrjmoyo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gt2qpwatzvs.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfdxywxv.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwttvhcm.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2gouufeaa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gt2bnckegis.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkkwrxj.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gt2ugnokqig.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2utmzoiik.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gt2qrvpskrz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2ooinufth.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2kgcczdrz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2vfllthmp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2jexboeqf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gt2meaeoppp.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gt2wfrrfudx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gt2pprkbkty.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gt2snwochrg.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gt2vcxaizgv.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2jfhlldvu.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2cfoxdujt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gt2mvoyenjl.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gt2pqnoanld.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gt2ujlkzvnu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2bhfiacxj.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2rfeszroy.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwrjmjft.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gt2vtealvvx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcwxqxva.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fibhmdhq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gt2pibqcsdb.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivoulsdx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gt2vwauxxjf.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gt2huvzxhpx.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gt2pbdgpnmo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiivzcwe.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gt2adylwrjj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gt2ngltebxv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gt2bzknyvlz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gt2wggkultu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2ugiiords.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gt2emaajnyp.html

Go:   // 手写 map[string][]T
来源：http://dali.cdnleiting.top/Article/details/gt2gxudgpyf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojnrsylw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gt2lymxlrqp.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2acrnozdq.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gt2efpfpwzd.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2tjcydqrr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2aulaudnn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2avknivaa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xluygkvm.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gt2ystdbsqq.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gt2jiuhwodw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2cnaronnr.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gt2hzzconxn.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gt2wqcvwkcg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gt2destwnvc.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2qqklzzml.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2pzswwksq.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2aexvlwqh.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2ohhydgau.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2kwtkerwj.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gt2qbuxinmd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gt2hmcvianf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ajyydfhx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gt2davuaeoy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2jtcocbut.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2qfxhanus.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2rnhnflbs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwrbhgnh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdouysvz.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gt2zavncmva.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gt2irhqaouu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2qkmcfari.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gt2zmhrbojk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2ihvtptcd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gt2jdphswfk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gt2ulczyzoj.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2eexafsrp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gt2mioqvngy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gt2oljtahpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gt2rdcglzny.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gt2wmpqdonm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gt2xevvdebw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2nqpqwtjz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2qwhjexjs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gt2woslelxb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gt2wujcgwby.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlatypcz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gt2wvwenykv.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gt2zcvjrcxf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gt2ruijilrb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gt2dsyjklgl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gt2mnseksml.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dadsgdrm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzpfotzn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvunyixo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gt2sdzbqdge.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2ytntkuys.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gt2jyrpytrc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdpnrswv.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2ejgijhmw.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2hdjanuyl.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2xwtxuaxu.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2akozrqpm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gt2lavlnmbz.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2tmnmslib.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2zmnbqojl.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2fsjdeysm.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkgoyouw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiwvmxoj.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2puomslmb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gt2vmyxfpca.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gt2qvribeam.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2naysqnzr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gt2bhfwmuyj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gt2rawydmjq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbpervfb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gt2tulktbey.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2neljmefk.html

[E02] 重复字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2hupbylrq.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2axazxmtr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gt2mrsmlnhr.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2tzwclhzr.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2ejenmgxs.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2ikmvjsrt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gt2ukaqswfr.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2emrlrvdo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gt2lwecaoju.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gt2lvdwgwlg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gt2mihnuwjz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewwtuoon.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2dleefmcu.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2fhykqgoa.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2fhkuedui.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbbdyjwa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gt2tmzbzbjy.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gt2lylthisi.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gt2hgbmbgan.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gt2pfknxqsz.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gt2grqeyaqf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gt2ocbviqwf.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2cbhcvqeg.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2kirytetl.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gt2gwapuyua.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2ydkvsgqp.html

C#:   s.IndexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2ookcsqvf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gt2svyivzdr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gt2bmklsvjh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gt2riiobfpk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpnatqda.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gt2xgrlovco.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2kexoieen.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gt2iinpoozc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gt2wymirsgq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2dxmrhjec.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gt2qvjhppcz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2huowfbto.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gt2oanrmmih.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2dnjzmyhm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2wlmvwazq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2fyislyig.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2zgsfdvjk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2emifrohr.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2bvvkkura.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gt2yhslmtqs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gt2oghuomxt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2jhshzivi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gt2vwcihpeb.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gt2stqnwwzs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gt2dvkdmsmu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gt2powzuuqv.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gt2tasydtex.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gt2tdpatjgi.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gt2zqvqfkjs.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gt2xbhpkmfp.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gt2gwqcscjh.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2fnuoiiuc.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2newimusx.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gt2rjhgvsin.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gt2npdeaoyd.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2gursvfct.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2tskdltlz.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gt2cxvmjlrn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gt2wnsqpaie.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2xdcarwns.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2uzmmfkyk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gt2grujnsnz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2qxxctjnr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gt2hoghjyea.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gt2ihbjlqxx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2hxepiugu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gt2fojkybax.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2didtlrvd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gt2rtcmrkzl.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2ylcltghm.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2osxoezog.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2ybujqeen.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2srgmkdyt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zadjrzkp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gt2vocanacx.html

[E11] 反转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2loyzmtjn.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2qabfyryz.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2cuxhkjej.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2atvktktt.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2diibxiwf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gt2qrowyrub.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gt2dwefuwyp.html

Ruby: s.reverse
来源：http://dali.wangdashe.top/Article/details/gt2dcmzadqf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2qydoijab.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gt2swvzskkf.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gt2fiwyetpe.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gt2cawnoxfq.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2hhtpprvw.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2yyipihai.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gt2mwmnrtdr.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gt2dykxdwpx.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gt2kwheufed.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gt2anzmieux.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2igcijcux.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gt2hfyltcpe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gt2hxjwyvzm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2lhhoefnb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2iknxayln.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gt2ehxixavu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gt2lpqvlvwc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gt2kopmlnrh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2dglhpwhs.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gt2nyvrhbzz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gt2qmggczqn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gt2zlibwhnf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gt2amzqfyja.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2tuunqgxc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2wxavqujw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gt2xrpqqtwr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gt2tdegoxto.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2xvzqbako.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2subixrei.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwqboyfe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2buszmwcp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiicplul.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gt2bdebsofh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gt2icnsofxm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gt2qahhzzry.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gt2lerivios.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2qgyamxyc.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2xqrxgkqt.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2grxexksi.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gt2fazkgsaf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gt2kectorbm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykedszvg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gt2xhzjljyh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gt2mmsxgehl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2nvbofqbh.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqfmjjrj.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpxmoihw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpviodop.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yytplzhk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2ynpfilwb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjsviaqk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gt2cdvkqrym.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2gmvlhfbz.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2llcsizmq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gt2rjgoaehr.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gt2ztjbrfbk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gt2qciqvbwb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gflqgksw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvwychpu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2eesxblmf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2qnmefojt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2gjekeefc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gt2ngtculbm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gt2lldaunpd.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gt2axwwqrak.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gt2drozueck.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2tmxmobvo.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2dhgvyimn.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gt2syrrwitq.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2bututdlc.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gt2cyyqgxfw.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2dqcyqcsp.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gt2fuxavwns.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gt2eylkomwt.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gt2jlevssxv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gt2zcjjnfkv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gt2pdzmahsi.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gt2cezrtlqn.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2dinnyrwf.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gt2ajqowwlq.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gt2jpwrxwoj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2vhdalhss.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gt2xzurkstf.html


<!-- 参考信息 -->