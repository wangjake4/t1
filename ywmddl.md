代发 wailian999

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2qoifuktg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gt2hyahdkst.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gt2ahgsokgj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gt2izjcymvk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2diowmbzi.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzgboqqu.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gt2sawkogex.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gt2vflmjooy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2immmrxnj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2qprqwijn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gt2uhxzjzpz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gt2ddujdkwq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gt2tueivrgu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gt2sqmzhvfl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gt2ryzrobfz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gt2imtqpgca.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gt2jqadsdgw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gt2tbxxtfig.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2cjzcrgef.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gt2hzywugen.html

TS:   [...arr].reverse();
来源：http://dali.aizwys.cn/Article/details/gt2zyuplnnw.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gt2dxoheoqg.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2elctwzxa.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2iqlvflql.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gt2qtixajoy.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gt2dyfslmko.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2sesplcgl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2iianveoz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2ysidjmyu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2mhyxudas.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gt2nzlyvpox.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2xntvluqn.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2jdxkzvqu.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gt2zluibvnw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gt2gacgrbzw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gt2vktvohkm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gt2nsgysjkz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2juzsabei.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2pxnhpbbq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gt2fsvpgjzn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gt2wsgrfnua.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gt2iihfwvia.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2gtjlfcde.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gt2regfiuir.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gt2cvfrezfn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gt2aanrujtq.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2ecpzdmzt.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2tixfukjz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2ognqszyu.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gt2rjyzlzzd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2urcyklfv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ulyyqpuw.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjmciejs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2dxiuhbox.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2fvzkyesc.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2kydaloim.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2gcjaojdi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gt2dfruaftg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmzricj.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gt2qbavspix.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2vclyrfki.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gt2lboqpxla.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2tlkgshem.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2cxbcgcad.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2lbryfihw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2nrhocfzb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gt2ajoosuxj.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gt2bsaajwqm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfanfkgv.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gt2ztzcakav.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2xauszrfe.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gt2ejcneqre.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gt2ezbojppw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gt2ntgcltnz.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ccgwovrw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gt2thviqbep.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ppjkuhtw.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2ucegpeix.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gt2pozqgses.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gt2ovqhxghv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzbziqal.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gt2scqcdgoh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gt2xzvbthei.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gt2tomibyot.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gt2ehledxyy.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtlhjdmk.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gt2fqpqhnce.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2mafyyjjl.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gt2tscgchkd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gt2yffizikb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gt2bvzxixpm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2xdwwkgpu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gt2wtkyoipg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2ctcwxfow.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gt2svciedbs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2jfghqmeo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gt2fvvsauvl.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kficdwgn.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gt2oydtcynb.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2zpxwvnme.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2cninqonk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2dwglwwdf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gt2vcavfotg.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2zicbxrwr.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gt2sqivqdsq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.meibo888.top/Article/details/gt2ilcygnvy.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gt2xsswozpz.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gt2onojbblf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gt2nrgpvcjv.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxidbtam.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2liwfrrxe.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2hzdzgpdo.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfgnfyng.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gt2qwanzzvb.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2saadhxpj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gt2ghbavtvs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gt2mhgvemwp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gt2ntvsbxjj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2lnpcjfzi.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gt2gllyfzxh.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gt2fzcemkzj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gt2akbyrvqn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfkhsese.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2shfdeilk.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gt2txxjoycb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qduzpypa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2hxyftolo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnnveerb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2ohhcvqjk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gt2psvxhdae.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2joopcfob.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gt2tipxmbvj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gt2anlixupu.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gt2ftnhoiuk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2xdgwyzen.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gt2jjgokgom.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gt2pkqxbxcs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2wusxammt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gt2wspmathp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gt2foiuksxz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2lhmlicap.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwhtidzo.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gt2fhchbtnm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gt2xlrlowlp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gt2fxqynvwu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gt2xbwjaanm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2chfrupvw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2pwjmqmkh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gt2upnxzdfe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gt2aacgmgml.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2cqwzesfs.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2aljdtzry.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdekstfw.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjblecw.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvlkspm.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2ebzlpkzm.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2mvemdxju.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gt2brmbbeqf.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2qhbztaal.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2uucqjsts.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2gkfqcifs.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gt2qvacmtql.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2evjgjfpm.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2clnggoqn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2kcmlezbs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gt2gurxanvz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2fwmdpngk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vborapnh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gt2kusratql.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gt2euuwiril.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gt2pdjusgvl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2kcxbroiu.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gt2vwhzsmmu.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gt2nptekogr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gt2xfppxzrs.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2qhnqinbd.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2kygpvips.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2acfzcebl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2htwemsna.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2mofiexsy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gt2bktnlhps.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2urexouwd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gt2iezbmucu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebuerywz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2poepqhrh.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2rznlecub.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2dunbupkr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oixouhux.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gt2gvwkpayi.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrejyynm.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gt2ftukrgln.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2oyuiiofj.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gt2vgvtiyzp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycatnlor.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvqncbdr.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2yboozmcn.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gt2awbhkqtt.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfrerlor.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2vvddsiel.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvxvwbwv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2duprjcxc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gt2womtvuks.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2ysjbxhbf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gt2wekciwgt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2ayihqhuy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gt2szkaetmn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gt2cmyplgvh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2zqvezogs.html

[E06] 替换子串
来源：http://dali.chenlongwang.top/Article/details/gt2myleyulz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2seiwawwm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gt2gwofefya.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2semnwpur.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2urtaxlqt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2mbtjwxio.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gt2grrtriyx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2hdjfkupr.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2ytqxxakc.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xudptqzu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzitmnmz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2lpzxqfob.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2gaqwnikk.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gt2sxvdzgat.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gt2sutywqpg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzsnttav.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gt2xdjujbga.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gt2kmynbudy.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gt2kmjoxlyu.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gt2hmcylhjd.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gt2kuiffquv.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2wjzvkksv.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2umghewqu.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gt2phosjahw.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyzxrhzd.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2rcfxrcbs.html

C#:   string.Join(",", items)
来源：http://dali.xziqi.cn/Article/details/gt2kzpmhwss.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvtuiigq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gt2vqkrsgkn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zumazytt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gt2tjunwkmr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2vxvxqoec.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2ygoincyb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gt2nkilhbis.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gt2pgrcixae.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2bxmevohh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gt2cjjbivgh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2jteloxrs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gt2hcarxsrl.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2eehtczji.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2aucmwdlo.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tffcudnb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2bnprbarh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2mdigwyau.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gt2jxjgoaps.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyysvhlr.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2wquojaeo.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2blrzlxxu.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyvykmru.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2akvylavn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcpvbamn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2qvkaswia.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gt2zwxrfuna.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2aqqcxvwd.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2ohhniaxs.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2ycuhgajh.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gt2opqqxfnw.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2kxrvvpmu.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2aureegef.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gt2cghicmmj.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gt2lbghhmdg.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2zjzjsltu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gt2csvyzmst.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2geobuxkd.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyuqffcf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gt2gohkfsrf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scctoxti.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2tfptwlvh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2fmvkeecp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gt2ifrxewwr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gt2ptgzkehp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2ztgjeoka.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gt2nlydppwh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gt2mqaonhvw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2thcgbagz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atvzvqon.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gt2cubxwnvh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2oawsspau.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gt2hgyfqdyp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gt2emgnnzpr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2dkscllhi.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gt2idhksejy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gt2pvarnlbl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gt2dcctizph.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gt2gbxfjyza.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gt2gnheuhuj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gt2fahszffb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gt2bhgslolb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gt2cxfladdz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gt2qvdnqwav.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gt2ngrccwkz.html

Py:   f"{1234567:,}"
来源：http://dali.shuidangran.top/Article/details/gt2plzwqeys.html


<!-- 参考信息 -->