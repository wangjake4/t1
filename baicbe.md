代发 wailian999

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmotzyyt.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gt2txmrqpyw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gt2axhvrmsr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2dsejphni.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gt2owjooqhr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2skbnnpmc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gt2cqhigyso.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2egeijuzy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycxhkqvt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gt2hiwlfnta.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2ajhdzamr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gt2ohflpjim.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2frziqgma.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gt2apmypvvp.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2iyzfawsa.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gt2apfwuiwg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gt2srtmwmbc.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2qonaduat.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzepspfa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2xclxeozn.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2kkxncusr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2mievzenp.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2xiswhdyg.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2wgbkvxtp.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2jgzawypv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gt2hovmtmwd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gt2edzjezgd.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gt2wmdgjyjm.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2whgxukxe.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gt2pzzffdgg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgmepzmz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2qcebrksb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2ixqzendx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gt2vphomagb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hyyztxvt.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gt2hbohditk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gt2znmzecnf.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gt2lauzgnqn.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gt2gieufuyl.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2bkatrmsk.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfcpjtxg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gt2lrixvxfj.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gt2ppvreflx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2kttmqcid.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2otjrqqya.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gt2gxsomxgu.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gt2pftshphp.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gt2btjpbsfe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gt2zhzoxdxb.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gt2qcbqnmcm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gt2bvuydthu.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2xrewyrbw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2idkacpkm.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghmbklug.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gt2andolijy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gt2tykpyidh.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gt2wdintwpx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqjgbnfw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gt2insszphw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgufenzy.top/Article/details/gt2tndirpzm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gt2lvzzmytn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gt2mueqnuny.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gt2mwuadmla.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gt2ywbwrryf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yonumen.top/Article/details/gt2lbezrrxf.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2zppptbyz.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lajjtipd.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2cjyqektz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nbljksrw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gt2ftzibmrf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gt2owmjwnen.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2gofmffbv.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2ruqdockr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gt2lythlyml.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gt2uoliemtz.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gt2ngntgslw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gt2bofiwbhy.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gt2bovgwika.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2qeyqexoj.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gt2tehfzmnn.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2ndpivtrf.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gt2foczxowm.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2yhfcooco.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gt2waaqqrzj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2leqibiqw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxgbopny.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdnpimxg.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gt2mrgijtek.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2xjoamkdq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2ahqcgspn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2jqeuxuph.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2bwxjxdds.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqiqnuip.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2pybrfhfo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gt2zilhbqwl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2zrcvatvk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2uumcrwut.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkdkfdaq.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2abptjshs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gt2fjvicgxf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gt2lifvcwyn.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2xysnpixb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbtlxero.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2wihgnoxo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gt2eiorqbdt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2llannklo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gt2qxamxmoj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkscpwtd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gt2rmdaarnw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gt2tecffdqz.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkclznoa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2ytnvhqvz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbbgwobi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gt2bzeunxob.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gt2dfwitsmq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2xaumhmtp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gt2khkrqthd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqcgeqmm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2rsxqboiy.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gt2qaejgwnh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gt2bkiutykd.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2bffcjnyb.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2tskqzupt.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2akjpkxih.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2zwtbmyez.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gt2ehyznapo.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2ivyosxyx.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2jnoajgwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jujniyhv.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gt2eoiaurhw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2wvdkoivw.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2zuubmoqv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gt2hvxurvqc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2hvjvliek.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xucbohcx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2qafagpyd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gt2xhnsuizj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gt2tlhcvdtf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gt2odhuohyr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2eptqrrut.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gt2ybbeazbc.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2ctgolciy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2scjyxksd.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2kudcplbb.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2imbtfwgi.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2hfafmvtx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gt2bogspcfs.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2uhqaghkd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gt2metgjoxe.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2yaftcskn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gt2txkofcxt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdnrixqx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2ekkjrhwd.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2tilxjxzx.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2uukpxbbv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxarlwar.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2pazbylto.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoqqodz.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjdehaev.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scclzcwh.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gt2oiejwniw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2moxrfmmm.html

TS:   s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gt2dunbnbte.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2hcwpgxkv.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gt2xvglcjod.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2smifahhl.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2shuniofp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2lqqqxawy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2nqrdvgqg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gt2pwmuvdku.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjpcsojv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gt2ycmxghhz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2qtotbmej.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzlscfrr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gt2eooakbcr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fanqbeda.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcpyssaa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2jqwtupwi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2owtwymuh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2codknnpj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2djugpqgp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2zwxyyxci.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aewkjqjo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2casaedkx.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2quvyjbyj.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gt2yhacvuif.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwjbybwe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2xfcglmxp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gt2vwpxszpb.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gt2spbrrxap.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gt2fchplyjq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gt2nmlgjtdd.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gt2epkadlqn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gt2ofnauepg.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gt2abynvgci.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gt2srovwklk.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gt2smahbxqe.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfxorrch.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2cyfibbfi.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2jcpqmkqe.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gt2tjiscywr.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gt2ptkewhch.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2psmrclhe.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gt2zogsrblm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2bxenbsbu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gt2fpxknnzq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2clbwjnmk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2twqovttf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gt2dnzwykgv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gt2ddsngcou.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gt2qiifjemk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2ipfyklto.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gt2rnfwkshx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2bxpmsmzv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gt2afwpcqai.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2zzonolxl.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2onhdzunc.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2cukgtxeu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2swqhybcs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2gavjlqtd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gt2fnapdamm.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gt2fypdvupm.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2avdqsfek.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2qymwgeps.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2kimhqssp.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2uifwukbw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gt2zhripblp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tchedtqt.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2bbqdmlrs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajonjtrs.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gt2ltvwctws.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2dszrplav.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gt2jjvqpaxs.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gt2lsqlhvko.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2amnglzvx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gt2ahsubhxm.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gt2qslzwqqw.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2zqxpkitk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gt2cklaebhu.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gt2ffbsevfh.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gt2yhsuzkqv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gt2ikqejtst.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnwneawi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2ogezvyqy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2eiwcronr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ncvpvmsl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gt2drvjbdht.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gt2rplmqcpq.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gt2pqubbacb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjlryvoq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gt2vcioodll.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gt2uduwfloy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gt2wkuhzgqv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2hrluaikf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gt2fwdzuquq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gt2wboajafq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2gmbztypd.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gt2dkjrfquj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ceixscqc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gt2bkjbltxi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gt2sysuqdck.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbfskkvv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cboehmew.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2uahoxmkl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gt2wcsahvku.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gt2lgtxppys.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2gguftubx.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gt2tjhhnffa.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfrvfwua.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2hctvbfbb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yccicdpx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gt2aqcconse.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gt2xduesbes.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gt2vnwwgwiw.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2ruuwunis.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gt2mogozzpa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gt2frfhpcyk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gt2jonmtwrz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gt2dyibfwtd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2fiiwpfbj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gt2ouvlgiiw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2qvwhowqm.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gt2unkeextu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gt2muadoayf.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gt2zctzlxpq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gt2zbkbedkv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gt2rlbadoqy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2lvowiktd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2gjtbxmyt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2uxdbiwse.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2hsfkdtvz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gt2jcpdqvas.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2usipjbzv.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gt2phgfzgxd.html

Py:   s.splitlines()
来源：http://dali.aizwys.cn/Article/details/gt2iqigjiea.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2uzveznpv.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2qxydovas.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2qxhtzzfv.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdwvttvw.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2tfoniefs.html


<!-- 参考信息 -->