代发 wailian999

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtiqspndad.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhbsepjz.html

PHP:  array_reverse($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtbysptclr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gtlhfdgplq.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtguelptax.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtrpaovqqi.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gtiudyygos.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtqafqzfyl.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtylvejwfy.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtbrisdgbq.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gthdibsdek.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtwfhsxuca.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtynszefqr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtgzveilqa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtmwxxgzxj.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gthnaxbisr.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gtqakrngue.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtlmysjcsk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gthdsrlila.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtwcuyhjyj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtfgkogixb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtzblyrdxl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtkywkwdjk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gtqodeebjq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtosiybkxp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnkfwythf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtgfwimpgk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gtjkxcvhmx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtzmudphuz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtjebebtjw.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtrjarbswy.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyswtyzy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtmqkbseol.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtxiscsvbj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtjhliloyl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtdqqqdnuy.html

[D15] 去重
来源：http://dali.guowangkeji.top/Article/details/gtrnotayvh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtxwwlhvpt.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtvwnikegl.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtuebbkfoh.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtvrfpmleh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gtiqqxxktx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gtnlytqhhp.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtvxiwalwz.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gttwqvtljw.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gtwqhlnukd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqazglua.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gthvqbzikq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gthnhgkwwt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtoppjlqkk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gtmuplhwqs.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdevgcod.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyclojxh.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gtdxttaixg.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gthfcsgcpx.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtegphmcye.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpbkhruk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gtistlohig.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtbrplnemf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtwlilmpwf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gtzhixyhri.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gtpzcuhpwz.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gtwmxpdcyc.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtlpvzgjoy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gtjfpzcfzc.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtxxrunmah.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtdsklszpc.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gtjnunslhj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gttlwllzwa.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gthvfkjvcs.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtelexgyyn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtbjwbqxhj.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gtrzlrgcle.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtfjwfvsoh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtupxmeqos.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gthidldcyv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnpktdem.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtpihaxqbh.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtyniiemcq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gtuhlhtsce.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtemdsenze.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gttjhdvuvl.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gtskzfdrlu.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtxvopuxkq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtlraoocih.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtwdmfcfsi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gtnrbdkohl.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtxjbpckxi.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gtbcyufwil.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenjidiqi.icu/Article/details/gtsgigwxpd.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gttobshnhk.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtwoetekrt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtzvmnlaib.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtuccxzsvw.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtlguszmbf.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtcdzdyytj.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gtvpmajjvk.html

Ruby: arr.include?(x)
来源：http://dali.yj20258.top/Article/details/gtegmfsdyv.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtkwqluaad.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gtennadfeb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtjykcwspr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxaahezs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtwrsfxoqq.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gtfoydsnjv.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtibewwltq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtnflmgzvm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gtnlhmyyvn.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtgadnwiuf.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gtkybuweng.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gturyxfvbi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtuvuacasp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtsoeenosd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtlmzcwkqq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gtohikhuii.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtcmtxvgck.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtqlzybwtb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gtkeqmtzsu.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtayliqrpb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtuqdalito.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gttowkkoyr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gttkhsjxku.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtzxpuzloj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyurhwdb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujttycbf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtonhmcbku.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gtpubbthqh.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtpcjwykyy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gtdbyobfpy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gtsqjnduuh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gtroapmueo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gthnaafwzs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtzjuovljk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtmkpwuwnm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gtqhydghkb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdtkpzkak.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtfkiuutxl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtsvjfrklm.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtkonnpaoq.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtwleojjos.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtiqjfhcdf.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtgqebqpgf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gtpjupnawk.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtyzzhpity.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtqwnuoaly.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjndvtwnp.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtgiljjgih.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtmbdfoozu.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtvldujzsl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtrxcztzea.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtmwudepgg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtpjehgexn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtyeddudcq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubyyhpsz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuxming.cn/Article/details/gtpdjlomjv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gtbpiusrqi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtzczrtqmp.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gtyqfltbpw.html

Py:   "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtvmnmplzm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gtgkezxxfg.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtqjmdlaea.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtzcedfepl.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgtqujux.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gteukbxhfp.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gthxdqmfqj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gttnzhbohu.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtsdoyfuyo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gtulttgiws.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtuanstxxe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gturjkekws.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtkehzzklz.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtwvedsggi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtpdfxpjxo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gtxlbxtvvj.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtphtlxeii.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtxuxvywgm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtkgebsgqp.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gtcyzrwapy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtjvkwvujs.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtawmehpzm.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtoxoqgazo.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gtqvbvbwki.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtcbybfmbd.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtguvqbzoo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gtpfxwicgg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gtsxrkqvkg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeskakvh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtpwrvmfru.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gtgzqvtqof.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehngwiae.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gthwqehdrj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtljbvhbfw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtnsnbijpz.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gtrwzckwka.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtycipndww.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtxigtxsla.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtqjuwdhma.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtsnhdgrjs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtgbeqonrv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtxegeohhy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gtyhpcylty.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtdobgvwlt.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gtcfruzakm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gtotobieet.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtehnuvnso.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgaffvgx.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gtjvzudvaf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gtqezvnovr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtiypyjcmw.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtbrwbcwgl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gtejsrbysq.html

[E08] 数组按分隔符合并
来源：http://dali.jlsjyb.cn/Article/details/gtfhwnnqfj.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtdqrcdsdf.html

PHP:  implode(",", $items);
来源：http://dali.gzhubu.top/Article/details/gtrfwlsgaw.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtyevmpgug.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtydbeuahp.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gttzfxlkkh.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtvmtqcdhw.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtwbitqmdc.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtefhgjmky.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gtawhcjjbc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gteovkbwgk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtenvlxonq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gthwqsdqll.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtjrhrsfha.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtalskplhq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtrqcbdoew.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gtyjhouhde.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gthmbaknwy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtddqlnltt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gthfkjqatj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtdejkdeay.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtmgzpicbp.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtcmeitcac.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtvaryprtk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtykxmqgku.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtglxlgqan.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtnztbtgkl.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtdxbyoavz.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtspknezkz.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtfdhkwyxm.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdquuhftv.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtslkqnpvg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gtbzrqgzyc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtepqeavoc.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtenzjftky.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtkjoaqvff.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtvflahmti.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gtqfdngziq.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtvcjxbejj.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gttpcwukfw.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtskkbbkbt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gtpmswahco.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtusjyvirg.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtxbrxdzez.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gtzaiszyqc.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gthzdlvbux.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtsvbtmufn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gtgvjgztnt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtdnicaard.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtcdhpdvlw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtdeeejwtp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtoyafgkjn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gtlbmfyrii.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gthgftscta.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gttglpmsqf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlffoqggy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gtozntaznh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtbgtewtba.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gtrwsifcre.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gtyvnlmzwg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtwdzsqfop.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gtfsxsgfzp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gttluzvyif.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtnchguddy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtebkajcuj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtjdeydccx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtonaxpsox.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtatqjdbfd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gtwayxgbaa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gtrvxnmgls.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtnznjzkom.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gtdoenguif.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtpidklwng.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtdjosiwxb.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtlladwvho.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptkjqjza.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtbdhxaztl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gthgrbfcyd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gthzpjlvrs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.316326.xyz/Article/details/gtpyuojesd.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gtruupntbl.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtemzghetv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gtcwnzvchi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtnoksxxgr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtttkuqrfc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqqsrjmof.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtunfwdtoh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtnqpptjuz.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtwkjloyle.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gtydqhwwdu.html


<!-- 参考信息 -->