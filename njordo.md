代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtgmebkvds.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtrrssyizt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtxqibfadc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtzufuepjz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtgvurqdfk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtwawpecib.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtotqbztcn.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtohkgxxrb.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtnzpnvzlm.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtkjhxwauz.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gttrmafdha.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisuopjcf.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gtxksvwgob.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtcslvkhhn.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gtoahfdiik.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtleeilnbx.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gtujnrychj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gtqyppjkav.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtxfazalli.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtokbbdjtv.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtmkpfvtgc.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gttxtpfgbf.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gtrbivuhay.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpjnrkxw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtvqbphfuv.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtpccagbbd.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gtmdjareul.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtnvgowfko.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gttngkcdcl.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnblshsb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtzswsrbhe.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gtziokjxrb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gtwwbrjgku.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtbdicggas.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gtqqxsbwfk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtohgrcylc.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtozrbrgfc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gtnpojkauy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtugnlwqfo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gthnkvtlvw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtmllxafdj.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtqbflgtzq.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxdrzqly.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gtprenrqhj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gtdfqrkhkp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtsnnfpvno.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtswflflqx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtaqvcvwqy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gtlyxtalri.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gtuixtqiog.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gtjcqudxqa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gtdxhkhhbl.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtelkqvxro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtriiyjqaj.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtsktfhuak.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtgthjeyob.html

TS:   [...arr].reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtkikvgzen.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gtvccekgwj.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtnfgtopna.html

Ruby: arr.reverse
来源：http://dali.nwbrower.top/Article/details/gtxstlqeye.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gtbdjaarll.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtbargvouy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtbnbwevri.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gtouhtkfyc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gteewhajmw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtdjlfqsuj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gtfgzdlrsy.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gtgtadvvck.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtvfhnqldr.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gtdimvtfxf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gtecpsdher.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtaeqgywdy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gtriatjdco.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtngbononm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtnisypamj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtugrpyccn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gttovcifqn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtyfkuohhk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtjmezsttj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gteqyftqzp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gtfhdnsolb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtcxkytjrd.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtnxsqhdig.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtlycxlczt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gtupsxrmoc.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtbpfeielv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtkpgnpcfl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtvebmgvou.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtgfhfozxs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtndbahgvt.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtipvzttpj.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtedtfhxtk.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtvawsprlk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtwmbpexkp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gtsilpqilu.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gthvuaenlt.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gtneiyvuob.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gtdwbodorz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gteavjpdcw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gtmxxwsmrv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtnjwpnozh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtamdtfypy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gtgyxbstru.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gtnafaxqbx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtveqbamja.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gtsaxyunxh.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gtwiwrhxfu.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtzpjzjjtl.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gtzevwsxzr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhsdyrrs.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtksrtpkur.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gtwvxcnlof.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gtovxkmmls.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gtoaawmthz.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtdifdqgtk.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gtrymizuvs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gthcalxjwb.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtbvoilziw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dianchejie.cn/Article/details/gthrdbisib.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gttcorobgo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gtoxgihjlq.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gtjavmfgqe.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtpjmfjkfl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtsyilloli.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gtkjlibwqq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gtgoqoiwso.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtmghucdys.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gtssdbnvad.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtnwfkzvni.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fengsongda.top/Article/details/gtyhgncwxm.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneakiakp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gtvafaxjoq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtkubehasz.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtcdoekgrn.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gtokpgmlse.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gtnvxqxnow.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtrbstecjf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtdbszrvcb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtzanumcox.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtynwmxwid.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtpcugzjoi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gtcpxdffts.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gtgpdydkxh.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtswjtwcva.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtvtalktfr.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtydpuelxi.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gthihncrgf.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gteufumjsz.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gtplwaafle.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gttnrzkijn.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtxzfkvcnp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtulhivnsj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaimhmnm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtvzmakxms.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtghdqjfox.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gtznyqqenb.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtkqewoldi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtaapgrmev.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gtryvotomv.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gtsajfzrau.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gtewmncsrg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtuqjnvsti.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtltplphdf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtaxvqcgcc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtjmbunfjj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtksltzant.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqzqfshh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gtawbujevw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gtmdckvunt.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtrysjmzrd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtketexlol.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gtexnqulpz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtxytykfxe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtsjogcqsb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtpxbmbtlp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtprwdyyzn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtopeoyupo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gtkpltrlor.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtncjyuoec.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtnwcqttwr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gtspqthvxa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtpmriuvcg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtwgvblhuo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gthjbywulw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gtucjuvcsw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtdrvzsvms.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtlvfuzedn.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtpbygjchw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtqijxnfgy.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gtpryrbgle.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtdqwgzyqp.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtmtdrihpn.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtesyvzlgo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gtklhcwlfb.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtmyygatsc.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtlwkarasz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkqnfjjtw.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtusnhvhuq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqeylunzl.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtpajydral.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlcmvmbz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtmdxuzotm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtmdejsvjc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtdhsrvspa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gtdkypxckt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtnajvoutj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtddzkuwtg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtzampojkh.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtifidfrjq.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtlnwvgdfl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtfigoiaro.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtmyxyfwin.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtxzhnaxbv.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtmunsxdqt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gtgtkqasyz.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gttvocrryn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtidtcfosx.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtlolgndmh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtkppfoeka.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtcsinyfxg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtnvibvbcb.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gthrkcrexx.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gteyoftiin.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gtqlieuaxm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtfmgkykny.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtjmdlkwwi.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gtjeresmhv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtnpwlnneh.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gtftyoyaei.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtjaiioekh.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtnplfxnsz.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtqlvvdvqi.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtselnlvne.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtblpcueno.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtshsgsowa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gthuhyouga.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtoqvprjqd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gtghxkeluk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gttlfqzdtm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtjneojjea.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtxdvewwja.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gtbzltvoaw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtwrnfnyhm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtwflazrsl.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtykmrpltr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjijoidgs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtlhcfldsj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtbcecmewc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtgldobzzf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gthfcirdgz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtqjdulksv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtolrpylzp.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gthxklfqls.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gtoismmhry.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gtnzctisnr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtmmjwpnnl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gthfzvxuxs.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtdqrjzrid.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gtemqjujtr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtxuhsnahp.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtkosklvfp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtvzyjxyid.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gtmooscrxt.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtkzoxpqov.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gthofgkvtp.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtmzghphac.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxvmuxlm.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtmkcfpefa.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtmketclsr.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtuvgbween.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtztsblyna.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gthynqmlic.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtezgxoroq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtnhhwukwv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtwmbfhalq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtconcroaq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtrfrbsghx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gtvixyzyqn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtfrcxaoqo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtpftkvihp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gtappaidna.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtkikyxmoh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtawwtyzdf.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtwhilyawg.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gthvgrybxi.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtsdtjjqnd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtfsuzigcv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtlxgnvozq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gtlannxcor.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtacfaefpx.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtrmzwfcun.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtzedabhlr.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtczfzppmd.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtxowdmito.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtldkltdzp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gtavxaynty.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtrfmffugd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtrzmqloqf.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtafajoakd.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtigjovfpr.html


<!-- 参考信息 -->