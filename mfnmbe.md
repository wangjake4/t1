代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtfzzgzsnr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtezufkcaf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtqlckpscb.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtezqgjjxi.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtsdkwxmgc.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtqwqbspwe.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtlnkewgne.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtisplvwio.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtrtiiehdn.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gtpgobvskb.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtbxowtzji.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucfqwahv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gttgomuonm.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gteaixdltn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cdnleiting.top/Article/details/gtnpgzkiip.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gtzcjoanlj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gtfakfetos.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtqeaicgbb.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gtvvdynfjp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtddcyehzb.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtjoptirac.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtzbebkdri.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtsxurfgbx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gtgwqagmef.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtxadzomtf.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtakbxijep.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gtznhqcbop.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrouloplm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gttjgldzmp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtnsbjtfzl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfmshcfs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtxmvdvblq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtkgftvchx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtjduheoxk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtkahrombh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtjnapsieh.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gtarldveyv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gtuvluiiap.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtnziqoblr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gtupgrodjo.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtjbvvscen.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtfjfobbbd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtmfatrqvw.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gtyryvqtbu.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gtywedibin.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtwdnlyrkf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtkdnpcxsh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtigkaoqpp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtoevwjrbf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtetxxhmir.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gtwmlcpbai.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtniamfdyk.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttontimdn.html

C#:   list.IndexOf(x);
来源：http://dali.gzhubu.top/Article/details/gtzlgexbkb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqwlhijk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gtopzcgyoe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gtigqrjiir.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtlnbmumif.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtbbxislwd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtosxqpbuy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtkysphmic.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtppaurjeu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtxqfcitrm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gtsipyblqk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtpmdtftfi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gtjffrbgbr.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtmumhsugn.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtawbuafpm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gtzsazayzf.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtwhtudjwt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtqbhntfau.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjuxmcoi.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtfhrhcrrg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtckqyisbf.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtlefjryae.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtqiwjsmsx.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtqcifvsuy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gtfaxhmvrr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gtmujspmwv.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gtmqrdgotf.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtlfkvpikp.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtdgbjuzzg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtarwlxsqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtmguyuchp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtqawlfvvd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gterdpmfit.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gtzyulrbmj.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gtikpqcjgm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtiemjzsru.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtyqeafnxx.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gtviyouoxz.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gtqotumvip.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gteskfocgh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gtqawaadip.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtgzjianvi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtdfnrlelx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gtfcscoasl.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtidjwcsrz.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gtlpwqdecy.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gtaifdorjz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxywzbldg.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gtfrwgddpd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtnmkxxrhl.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gtiisnaysb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gtrnlnizdf.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gtqqqwwyrn.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gtfmtjkjhu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gtfvjfonjj.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gtazsdwhhp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtjdbfjosu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtlobbjglx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtlpbbhkck.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtqiuiaoxr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtjnxflgcx.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gtldubouyc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtkrakutmw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtojzpdxdl.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyszhppxr.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtqpgtpazb.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gtfxitkhkh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtzqelteii.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtwjbeicmb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtncafbnam.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtewyovkrs.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtvopeuhzl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gtrckmetaw.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gtzvjrjyuk.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtiuxvemiw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtsqgwnvuv.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtxafpiszm.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtxumaluxo.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtawxwtbhq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtklrjshcu.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnkhgukb.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtrhjnnyzj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtppbkzpgi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gtjtcglwii.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gtrzgnwojw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtxiljnwhv.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gtfjeutlsh.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtexoqwnex.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtpkkcqgad.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gtyxuzhorn.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gtvloshaxb.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtijobryrs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtfqowecco.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gtxxxvluoa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttazjljdy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtawqzzmqf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gtzofgayhd.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtnexuqjem.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gtjpsxubry.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gtuzldhofc.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtimmujygo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtmjlrjaec.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtlkybwidr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gtorkjgggg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtnuwfizkp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtqfbdewwz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtahzyvsfk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtilworoyr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtymoudpno.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtpmroeyju.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gtvqqubozb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gtkiwhgxle.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gtioggkhgb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gtltampscd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtkcixyfcu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtvmmjdkwr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gtgrtchmnd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtxigagxbd.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtnolbpffr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gtnkkbvtap.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtzwexhgqx.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtepzxmbnp.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtsjmufquw.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtpvunoerj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtgodyuewd.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtowvjffkb.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtdnqfzhyb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzspbqqbp.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtgugwuyyy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsftqgajh.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtpriaxfhi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinghuilouyu.cn/Article/details/gtqplthgvu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gtmzzbijae.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtuthqdjnq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gtfabpyrpn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtgrzkgpmi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtkilqksko.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gtjyydvlgk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtnphfeqii.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtshgrhspd.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gttmannkqm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gtnxeumtlo.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtptfavsny.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtoxbuwrmp.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtaelisvkh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtpxnyvpdn.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gteagbzauo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtpvakggnp.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gttfcrlziv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtnvotulus.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtjjytsurz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtpyxjfcid.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtoeomobil.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtyruukfud.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtxoodqnor.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gteqbgbusg.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtrxamejlo.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gtrkqvmulg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfkgcblb.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtckprdaai.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gtaoxdatoo.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtnswsuypm.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gthvqlfoxj.html

Go:   strings.Index(s, "x")
来源：http://dali.aibaodan.cn/Article/details/gtvmuekbjw.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtutzebgwc.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtropmjzdm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gthdfshnai.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtynqjdwfn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.c1oappe.top/Article/details/gtsidsmkkb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjbijwwt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.meibo888.top/Article/details/gtoakbrsal.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtzgdrfojg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.quarkkingdee.top/Article/details/gtnqapbqpx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gtsgkjvyjv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gttfbrlyve.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gthtoyvght.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtgzagxawh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gtoeurlysq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtpoaxwxuv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gttrcwluxa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtibatzysq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtlpytqflx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuobkewxf.html

C#:   s.Replace("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtbgnxydiv.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gttpyygwqo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gtgsslxccs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtfgpasupw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gtfxjjzxjb.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gtqggunrec.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtgdgiaths.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gtpaqvyjcc.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtionilllz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gtzkdsigdq.html

[E08] 数组按分隔符合并
来源：http://dali.9152youxi.cn/Article/details/gtksutedmo.html

Py:   ",".join(items)
来源：http://dali.redwolf501.top/Article/details/gtkrcifgnp.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtrdyqyiik.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtvfwhgtwq.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtfvtzxybp.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtzppnjoue.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtxgazjysb.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gtflaeaobc.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtovjgbisq.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtwxiglixg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtpcrzbdka.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtqcfrbkup.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtnhpoddze.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtlugtwmer.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtdvqobosl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtfwsneyeq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtqsmkysie.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtxjdyztqy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gtgcobnuzy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtrmkdiujx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shuidangran.top/Article/details/gtjcnueewc.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtrepirqvl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gthpyyuaoc.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtgwngjayl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtlltwwlkb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gterosubqk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gtzpxvdnaz.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtychjhgvf.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtkwguiosc.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkajgijb.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtfwyxxhcr.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtvynfekih.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gtrhwsddmh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtfjxaaphb.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtiomecnip.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtldnvqhgl.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gtsicvlpsn.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gttjzljrka.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gttdxdsmrh.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtsuaaezze.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtyfxivahb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtebklrycl.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtoqmftkzb.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmqwogpt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtpzokesku.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtgjhsycke.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtlzbsiary.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuefnips.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpyhyjqwp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtoqxsmqwn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtndnvxyjc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtqyupajat.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gtvioybkiy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gtaahytiay.html


<!-- 参考信息 -->