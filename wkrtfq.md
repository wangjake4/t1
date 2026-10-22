代发 wailian999

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtheickcqd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gtsliloqsg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gtcmzohsuo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cdnleiting.top/Article/details/gtrxedwsth.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpomfbmdp.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtzawtwgjk.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtscvkyqsn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtfykxizwq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gtqdrpycki.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtzvpvadid.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtskojueft.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtudfywhhy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuvkitxr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtkukmhrkp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gtbyfnmfel.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gtduqiygva.html

[D11] 反转数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gttksexonk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrqqofnx.html

PHP:  array_reverse($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezztzrkf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gthrswhpvw.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtehtmimlh.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtzvzijmmt.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtgthddbvs.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtxhiraxmt.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtmxaufeja.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtghdxsljx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtvoqubpbb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtgdvssrki.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhdvpsnm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtoeowstdx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gtyeluzzho.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtzksuulww.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtimovewwh.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gttyxpwzvz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gtmepxgjnl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtwwrjeqju.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtpmwarpmh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtprloqcfx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtjtiqbddz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gtieogrsyc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gtihyyshif.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gttfytzkkt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtmyhkcgnu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtopxawoqj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtgvduxtrp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtctzgkmcw.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtdzjryvxk.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtsbksnrwe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gthdlglbxx.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtlakeqdrj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtzcduaksk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtoogjldsj.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtndccjhlw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtzfowphzg.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtyxzligwa.html

JS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtjredrihw.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtkersujwx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gtgjxkqstx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gtbntdovqa.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtjcmbhgpa.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gtixvpucvy.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtzagjfqcq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtesaubuku.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gtlcocipvv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtoecwpvgl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtelxiqvny.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtpeejvwig.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gteimuuflu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrqacevx.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gtqilcsxsj.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtlgzzaghc.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gttewcachz.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtrqhogrst.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gthvllkjpn.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gtanghfjst.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gtngtqkuhk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtwlwngmnw.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtvxuxbjmj.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtxuvwljek.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gthvynstux.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gtjtcuiypx.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gtfodzzelw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gtiwmmibxn.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtwemofwvl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gtjoedwrto.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gtdljdhipu.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtaxjanlew.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgdcgyfk.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtkhxigian.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtqxxoeejp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gtpncmcdku.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gtorntmlgq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtuqbkikui.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqisblyxg.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnapibedd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtjzjybhnu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtotcldnci.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gttkqxlxgz.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gtqwhscbza.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtkkclvgbt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtptphlgzf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gthsfoimvx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtufskavsk.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtnihxrbvd.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtbdfawxys.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gtpewizywj.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtxavzrbay.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gtlkkrasrx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gthqgcifjn.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtuvftsobg.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtvorwqxef.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtallhiuwm.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtdhmcwmmv.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtnatekdin.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtmufqeihd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtvdpcpggf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtpnqvngru.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtkzamcljd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gtvgjhtuwh.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtrdnswnjn.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtmxcxajbo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gtsuizecpx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gtdhsirhxn.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtcmxgmqgb.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gtkbjxlery.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gtuuzicklu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtrmcklpku.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtuccbyizb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtghojpcis.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gtouecfpkn.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmugqrhfa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gtansjmeyo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtcehgdoyl.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gteucazfir.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtdtifpdls.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtscnyxwgy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticymehuz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtjxsiacnv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtwjqjburb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtyzhxvqiq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtyuaeizew.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkezthjb.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gtdllqcltn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gtqhbcdvyi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gtlzwadtpc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkwfnrppg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gtmfaakphl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtkpkuecpy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.kuanghao11.cn/Article/details/gtvuarevmd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gtedumjecv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtsbxqogey.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gtctvipjsb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtkweeitwf.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllyspxon.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtdihxpjby.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtfcbrpnbw.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtykknwtbt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtuwuqpuxb.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtxdvmsocs.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtsgptcphe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvlvqoegi.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gthuloptdf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtxcipdrby.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtpjzqixzz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gtjtjiukdk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gtawoyrtlp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtiajtvfyr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtrzfbaogs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjivumhsy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtgjsbwuit.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtqzlbnoli.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtzaozqvti.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtpfaracme.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtyqryohwu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gtawxkjsvq.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtoxzxegff.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtauclwlag.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtauzokdas.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gtzdrnprph.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtfvxpxmfm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtabotuksl.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtkogvprsj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtfduyqjnp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtayklpukv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtsngoaclj.html

TS:   s.slice(1, 4)
来源：http://dali.yueranfly.top/Article/details/gttijthotm.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtbnljrgjx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gtvjzueqmp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gtbddndzxv.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtetdpfqcp.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtywxwztox.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gttraeaykd.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtczggqzwp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtpvgoxsbw.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtpqamfsjd.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpegxiwyb.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gthhardmbd.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrdqxkcv.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtwmiarqlo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ivvv.top/Article/details/gthkiaawgw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtjqpfapzk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtmotvbqgi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtdmndiacq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtpfznthds.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtivmrhhty.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gtueleokhh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gtnnqyclar.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gttiwgjgat.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtoczwodow.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtboqhcijg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gtouiefeqg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtmhattddc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtmuzevjaf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtmnxucltm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtvlhoqdhh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtjjvalpvt.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtxyqvvlel.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtdaohgtvt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtohvmmrao.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gteskmmzzl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtnkvvazmx.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtlkmthsmd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tian-w.cn/Article/details/gtlqfmardf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gtvevvcphx.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelsmwppe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtwgohlqqk.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gtnbbezycb.html

Py:   ",".join(items)
来源：http://dali.andypj.xyz/Article/details/gtlmcqoykq.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtxetfqwik.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtrkfipnqk.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtuxjlkaio.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtwhnjhnkv.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gtumspfpod.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtwhzkjihq.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtrhjdolaw.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gtppufxfcb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxtxiadnk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gthhtwciil.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtdzjuajhn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gthvqqnweo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtqmvkvspd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtyrinryjq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gtebuaixyh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtfqhnuhos.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cucudq.cn/Article/details/gtqpxupmeu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gthvuciatb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gtgcxzyvlw.html

JS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtiylvazwv.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtxdkywfny.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtgdbrbcqq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtklgdqfvg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtlmcbfsxe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahzlpnux.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtxfbvvgwf.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtekxlqxml.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtddqeuqzk.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtrnvbwoex.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtbuitybfj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gtwyjjqhbj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtsahqxysn.html

Ruby: s.reverse
来源：http://dali.wangdashe.top/Article/details/gtzltuvmdp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtheiezgtp.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gtwbpijfcb.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtuipekybj.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gtqzwaylxv.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtxidmkzwa.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtsezknhyl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtuhybxgmp.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gtngwtejux.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtcramdbkt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gtzhmotxvy.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gthlbzhyah.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gtqfyatesk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtmxwbghvf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gteablykmu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtsyeyabxx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtbckeyyby.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtprdedhrd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtmbgrhiej.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtauvpnyyg.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtergrzyzn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtunbythmw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gteljlgkzs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gttlbzeolj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gtamfnvjuo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gtwubqyell.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gttuqjcuws.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gttdozaemb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhkpafsz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtninuldha.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gttwryadmp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtauvyjjhm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtiqyfnzjz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gtrwuzdabl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtpvapqeub.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtpjiluewv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtopccvphk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtysvhpfeb.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpqpqslq.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gtwtdjcgia.html


<!-- 参考信息 -->