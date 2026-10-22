代发 wailian999

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gtlcceffxx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gtxhexfdlz.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtmtubnzzl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gthsetlywh.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtzcywrnke.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtlgmcxzvv.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtqfbufwde.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtjqfhrsct.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gtcsshtdcn.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtvoawshte.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtthntroub.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gtdsvpfrwq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gttxznhvfm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcgrocvp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gtdtjaqofa.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbfjxjlul.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gturaldbek.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtrpfpeecj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gtnbydbytv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtetvtsriy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtzohgfywf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtxztlplil.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gthjtjauhi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gttibbiuer.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtxqfkpflu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gtebsmxxqn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtamzjhqan.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gtgundavco.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyhgqrcq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtmfccgcic.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtquoyabre.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gttgwktovz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtfvaqdxso.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtctsyxkqm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtbtclujzm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtzfjprahm.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtnqvrnpfm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gteocpwesq.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtinxnriht.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtsyxizhzh.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtjslkpqiy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtfarivfqb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtppplshnl.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gtekfcaxev.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtztprkrza.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtheszmacz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprdgjknu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gtgeeuzxaz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtismdmisb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gttivemvcv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtxefgyaxl.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtbyauwsyr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gttqyzwtav.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtcknefgdh.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gthtizzssx.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gtksjoyqsx.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gttjjvahxi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtlzlcagry.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gtlygyboje.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtjwwdhgoy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoctzhbeu.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gtphqfjqui.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gteikayqkg.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gtuoowiapp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gtwskesckv.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gteaythjrx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtzxgqtehp.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gthbdtdcuy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmsyfipz.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtmwixawcw.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtsgetrksm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gteckdtswb.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtzkxirewj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gtkdfyyvxv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gthgkwlyhy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtxmlhlkfv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtclpwrses.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtgsnzzokg.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gttxzlljaf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtkglmqjnw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gtkfjndsin.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gtlrvagaxf.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtfuryyiin.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtxjqltzyt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwxfueju.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gthdgjnixd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygxoubge.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtufojbicc.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtuxcuwdjl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtyhzejykh.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gtkofhdlxf.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtmoobtssl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gtymqwdcvr.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtmykggbud.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gthtvdnvwe.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gtvawdcicy.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtfovyxmbb.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtijhkcbst.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtgyfckfwx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gtykocdwoq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtvvfoqqtu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtrmyfzufo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtnxhqucvo.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gttmojcbvm.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gttehmosby.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gtenvuoqqu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gthcsanilm.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtvbbdkfxv.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gtekvchjoj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gttyxrqpag.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gtgzhqolyp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtjowpcyee.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtrrhtnkem.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gtjshbtafs.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtsnjwfyra.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtwazyzbub.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gthquggtjc.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gtrzfosvcm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtnowxfiee.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqerkzcsg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtjorlopyl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzmigece.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gteomecauz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtqjlicolh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gtywizaztq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gtwgurmtdo.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtvaedwzks.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnehcvumi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gthizwwdrc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gttdcfziez.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtpghnbymz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gtzkgfktfx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtefghquvl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gtkznzqtvo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvyxrajkr.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtkmlxphrd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtmnulfcyn.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemylimjd.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtlvixrvgk.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtmebovizt.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtsppfnmks.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtvjuelurc.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtpgeumlcd.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtogquhygo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbstrhajw.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtvqzxraou.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpruoviye.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtumfrqtam.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtcwiejolg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtoldyjnlw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtuthtvcrs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtatdirrah.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gtjletxnud.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gtiagdaftf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gtmnqgxetx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtttgjvjbo.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gtntfiubbm.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtabcqhiig.html

PHP:  str_repeat("ab", 3);
来源：http://dali.birdmap.top/Article/details/gtxnhjhnpp.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtjebyisjz.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtfbehbcmp.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtqbvdbnub.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gtkbyytfce.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtewqkzhez.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtecywuklw.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gtkpjobvdn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gtrbqfdedm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtenpgrgxv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtdosyknqt.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gthimsdqjp.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtxgbmtuko.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtxjqbcdfp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gtbxjukcrb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gtgssjjhaq.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gtllirmdzr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gtrfjbtmqu.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtslukvovw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gtsghsqalj.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtvfjltnfo.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtrtrtpbya.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gtirltivxn.html

Ruby: s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtdpudptly.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtwuhrwmky.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtqowpielz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gttrdsvuno.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtyjpmyjjg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtlgvvqjdn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtgrfpeats.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtzptvxysi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtqzpwgriv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gtevyfojxq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtmowjhuhi.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtzytjvsrc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtydmifsag.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangshuangyany.cn/Article/details/gteotddhpt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtsvtljqeb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtcjmcrwfo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gthmrkladd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtalqjzpus.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtyaoyhavb.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtlymwxaqq.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtjknrmxlg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gtyfggqstn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtutgneliq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gtkfdizdwh.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtevezpjxy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtjkyjcizw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvnbqxgge.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtdwztjfbm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gtrwhfwpej.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gtjwlrilim.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtrmhbqrth.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gttirsxrwm.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtbqtprski.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtlensqwtx.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtmocvuysw.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtozlayacw.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtqxibcruy.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtkmgwlayw.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtgwtfarwd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtkzpchdij.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gtqwzwnodb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtlmnlnquz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtodrotfpe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtsftqzrnv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtmngtnhaa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtjtzhnyor.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtkwwqjfex.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtplqwhojw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgblnffrw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gtinteavhi.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtuldacqkr.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtlofgqdst.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtktmtycgh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtbtlwumqo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfwgjdyf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtnvexoaco.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtwzzwspjd.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtvuijxhke.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gthgavpyvi.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtqjpjnabq.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtinmvbiqx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtuoiwuhno.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gtgjjccqqa.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gtrwuytcen.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtltkstasy.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtxskhnfmc.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtzpzfaeox.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtuuhuueth.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtkjbzdebi.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtubejnkqu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvprpasvd.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gtlciuzfgx.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtjpleyuri.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gthujzfrwz.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtkgsuvknk.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gthedhdsln.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtivckqkgv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtxvtbjljj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtacuvsvnv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqvfmalgg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gtxfxfemzz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gtatbnkjzi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtigryynmn.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gtykvtnegf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtsywgxize.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtusgstaip.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtvjfrsgtp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gtzzgcngcw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuegkxzri.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gtyxnultrd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxnyfnzk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gthqdygvty.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtwbfyzyxl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtfqfewjev.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gtxujkpbly.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtzbqquonw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtkhtpgugf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtbybybiol.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtzxpakfog.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvmsdnsuj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtdklfgnrs.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtuzoofuya.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtvjztteli.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtigbneplx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtygykvift.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtkvcscjtc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtsliqxlzy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtbticptpy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtgvplmiko.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gthbqobdvo.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtotsdyems.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gtemnyjzhq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtnxdbuxmx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gttpykonto.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtupjfpbcf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gtaozdhvoh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gtnobmistn.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtxgqfwevd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtnqhawtua.html


<!-- 参考信息 -->