代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtlutzjjbu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtybthnnvu.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gtzxrvsqgj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtyqkfirrf.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtmyyzyhto.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gtlnukanan.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtgfzuqnyp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gtanwlzafj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtgrtkelul.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtrcybqfxq.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gtqcppyngr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gtpekaipwt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gttwwvjjay.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtyserxzks.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtjkxwxrbx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtyzhmamqq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtduhkzsmf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtfckhumyz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gtyjxdfuzp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jiagoushi.top/Article/details/gtoftstxkl.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtpdjcsmfp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtzoicegqr.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtkhukcufw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtquuspgng.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gtxxcqbhhd.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gthddoocmj.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gtffysnaot.html

Ruby: arr.reverse
来源：http://dali.9152youxi.cn/Article/details/gtbyomvwln.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyrjwllc.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtmbeyovbg.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gtuhqjfapm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gthceeuuvn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtnsqwqrfv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtzmhuxrzs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtrtaptpkr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtakdpfvyh.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtsmmjjprg.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtxrqwzhua.html

[D13] 过滤（保留满足条件的）
来源：http://dali.redwolf501.top/Article/details/gtsjvmwwhx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtigiocjer.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gtnasdjqkd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtdnlvxuai.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtvzahjjro.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtesnndmir.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtdbxbcvyk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtblyxijfr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtxpqgrwsd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtzpklgznx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtqngjudah.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gtynedesxn.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtyaqpuxws.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtssnfzitm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gtgpnsdydu.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gturkznltr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtvjrkmpln.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtlbluvarc.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gtzjyilaqd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gteirpyjuc.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtujlzgvzv.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtgadxrzvb.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtlityhwui.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtnowchnfl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gteuopxbtj.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gtblduyipy.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtidgebelb.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtvmvdgwyo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtehsjouiz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtmghsyiqt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtareyifnc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtzptfgeur.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnuoxwqj.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gtsulmmzvd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtwvpcsbnj.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtckodiihh.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gthrwdlskb.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gtmssgzfyn.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gtozcwkbxf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gtbsamhetv.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gtxfpthkil.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gttzwikcng.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtofkkloht.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtpwtoxutq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtzpfqolus.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtubwgdmxa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gthlekgfzr.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtahbrfdub.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtyfplwcuq.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtecyinhrd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gtdjznijno.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtcvanunot.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtzfohzbzi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtnsuznsxe.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gtdylxalky.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtgcygtpqy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtzywkcexf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtoygtcgrr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gttncpvmmf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypxorlxs.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtmsuwjxor.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gtbzsgxgjy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtctecjzmp.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtgigyavrm.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gtfxduwhtp.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtcxasqwbo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtriysrpsu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtblzrnntd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquymcitf.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gtvhozckxy.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gtayutvqgn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmlsedpr.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gtaxbxehoc.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtolxizhtq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtdoxjxmrp.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtojttuhbn.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtjrfwvppb.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtpedcwoqr.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtwblnxptr.html

Ruby: arr.include?(x)
来源：http://dali.xuanzx.com/Article/details/gtoijhmzyu.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtgtnmqbzl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtfrvnfuvr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtoumpqwsf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtjltyfmju.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtikdlqrgi.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gtofjleixi.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gtdxyhdzcn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtlkiynlsz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtadmfmhni.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gtcufpfccy.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbonrpprb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gtpowygoqn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtzulsttwn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtqmduifyk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtsgecabml.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gtfoaeedxn.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtnkapdwrh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gtzsfpnmmn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gtujkwxjxm.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gteirtatnc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gttlqnayqk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtsetrhzlz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtqcxtkrgo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtgxxxvxrc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gtrypuqmjx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtweplikqi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtltnepzbt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzqfeoww.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtwnfejaqp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtzbduparw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtpgbswqhb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gtcxagbtpc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gtrovwyzrr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlvnqfrc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gthmgwhdjh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gtiawwyurj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gttlplbktw.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gtprjqbbkj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtdzalsexj.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gtklwfhzub.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteylodlpw.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtdlnagozr.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtlkmwuqzi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtysefnqrd.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtqtxiflvy.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtstrqhpvw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcxukwsri.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtkvbccqay.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtiisjwqjq.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtuujmjukp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.kuanghao11.cn/Article/details/gtqnabohhs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtxiakupwu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtaqgoimai.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqxspucj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gttrykcuuj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtnxxwnadp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtikieophb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtflcqkmsn.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtaqbaetni.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtcuglprhi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gttcczbfsb.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtnuektrtu.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtbgfcuslc.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtqmjozesr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtpczmwhks.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtctpxwdvm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.vqdsnc.cn/Article/details/gtshggtefn.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtyvprydap.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gtjmnvfcwl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtjfymlqxl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtisrcrdgj.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtepbnojkn.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtvbyobjvv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtbhjyqzba.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtjruxammm.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtduhtcwyx.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gtbzzywbqj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyjotmdy.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gtitfdxybs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtzgelwqnd.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtqrejvocj.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtuivmjiad.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gtuukbobmu.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtluvhxhkv.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtzzxqvxuc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gthzudyzuo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gtzfaxxhue.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtymfqkwlf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gthehyimrb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gtxhxbsbmn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtknwixbdg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmckcaegr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtwlhmgrxy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtwbdrbyps.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtwfwyuhkl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyazgkkhe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtnjzkqajt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtjqlodtua.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtdfkuheci.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtltbdbmof.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtbnmntbck.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gttrawlusi.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gthwfodxtm.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gtlprrgdmg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtzmpsmcgk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtoyihager.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gtnkxsekpd.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gtjvtxonss.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtomrxdinn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtwfopkefd.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsjukaaw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gtvpvghuea.html

[E08] 数组按分隔符合并
来源：http://dali.zhengqikj.top/Article/details/gtyezcehee.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtrvjugvfw.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtbmlottgu.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtmlcmoobi.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnojcvvfs.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gtafjvzhhd.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtppwltxck.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtajwopyuj.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtbjbmfrof.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gtrtuxunmq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gtpberayxo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtpucggtfv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtlmlopykq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtjjraeonu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtlhpcnhwn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtbbmvfmiw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gthbaegrmd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gthkvmzgyk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gtbaugocbj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtbuunreii.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtnmsfwkwi.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtcqbwndxy.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtpmuvpins.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtmowxmkxw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtwaohnpfl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtrqfsvoux.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gtalwjpczz.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtmveagaci.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gthlolqsjq.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtyolfcudv.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtlbzkgffg.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtcxkwoxfm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtlwxdtjhi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtneadkitx.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtkjgisxxk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtvgffcefh.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtnlshcgay.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtxcnooygg.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtddnsazyw.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtprjcnadm.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtevqkgmrc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtbpeavnog.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gtlrhkgnog.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtrkfdjiff.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gtbofnmpnk.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gtbmvbirmq.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtfcptmecf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtqrclqrjq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtkijwhdcu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtyygnswse.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gtigvooenr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtsbltavwa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtexzymwwj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreqebfeg.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtbhkgtrqe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gtlxejbjva.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtthdzvtbx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtoipzwhni.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtehxgrtfj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gtiudnssgk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtoisgaxmt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtkgechgyp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtryabxgfj.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtsgrxpihm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtsslpnzfa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gtitmapury.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtmtzqliec.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtwehxyhih.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtyavbhtjq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gthkkflbzq.html


<!-- 参考信息 -->