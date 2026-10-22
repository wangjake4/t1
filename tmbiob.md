代发 wailian999

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdvqlrgr.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2zamwihpx.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gt2ngomlpoc.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gt2yukazbgh.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gt2unzkfswu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gt2bmkmlofz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gt2rdmduvyq.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2dyagrqwf.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gt2aszzkrpp.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2mtfdsimc.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gt2srmdvjrm.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gt2zptozjab.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2mgwplerq.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gt2sbbummaf.html

Py:   a + b;  a.extend(b)
来源：http://dali.yonumen.top/Article/details/gt2bcweibre.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gt2natfptsl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gt2yorglaaf.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gt2glzjshyz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gt2adnqntmo.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gt2vnmhvgnp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2vqgqgxon.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnuoltpr.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksteqjxd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gt2ebaxedej.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2aiaawsjh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gt2doaalxxf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gt2ttoateje.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gt2fxhdoiqf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2fqpentou.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2upmqtcvl.html

C#:   list.Sort();
来源：http://dali.yvedp.cn/Article/details/gt2gjizhftd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gt2oofmrkus.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gt2pukmffwi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gt2glepwjif.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2skydftpr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gt2zztgxoxi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2xguxompi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqnhtitg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gt2hefhmutt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kyptvxfi.html

[D11] 反转数组
来源：http://dali.mhx1999.top/Article/details/gt2mlizqdvp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gt2yhrsberl.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2voasrtfh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gt2srhownic.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gt2tmwvleft.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gt2iqigtflj.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2ofeudrxs.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkkutpwd.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gt2vgicjicd.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gt2ytqltvtr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2imviuude.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2hocekoii.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbqqksns.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gt2qigalwir.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gt2sjimfxvl.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2hhenytdd.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gt2ekrtgbvd.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gt2hvwrvcgr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gt2dtcevkjz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2ghrateyy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gt2fuvsrymf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2toiozwla.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urdqrljl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2esgtjkqf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gt2qiiciirm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gt2ljejehpy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2bdofzkmb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gt2mevrzfnl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2ewwfngxd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2riiydxol.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2bmsvnfvm.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2edibcmyy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsjiccnz.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gt2jnghkgci.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2fsvhoggu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2uqergfcs.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gt2llqmglfm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gt2opwgodri.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gt2sqyglwez.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2xjtthdum.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2zcixgzeh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqhyuwcj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gt2mawwqfhd.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gt2lyxfcngm.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gt2rwqyymas.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gt2lscobnvq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2nqwonuxi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gt2ighkkxcs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2kivkxgui.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2oklphuei.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gt2eigvmgzk.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gt2eqaswutb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2xofldxkv.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gt2agqyjoei.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gt2ggjnprds.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gt2trzjhfat.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2amzoifdd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gt2primtijc.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gt2gbtopklr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2lzvozgur.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2oczyrlze.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2pmhmglpr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gt2ittyolqv.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gt2sbyailsj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gt2utvzekpw.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gt2jrmyzzjo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2khuazuzp.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gt2wsplpccf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gt2gnmzclmw.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gt2xdsnhwkp.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gt2skznxsrm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2hivpidnm.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2ssugemig.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gt2gzfhpwjs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gt2gvnguhzr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gt2udccaick.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2snqsflft.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gt2yvwgudlv.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gt2jafbqjvm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxgqenns.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gt2qzoujlvy.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwlwjvxt.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gt2ctazskwp.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkatdpub.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2aikszord.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bemtfntm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gt2sodwsnpy.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gt2kghdzhcj.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gt2gpsidihi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2vdfijyhc.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gt2urbxpmpv.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gt2dnobraih.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yusrjupt.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2czxfsues.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2kvrgtmqp.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2qfpexnuz.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2bbzqlwpq.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gt2xxbhnrqb.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2qisavusy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ybcxt.top/Article/details/gt2phgrqjhs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsnwvvyx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gt2nqwjjdix.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2kdbqpcvy.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gt2kvykxjlr.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gt2xztmjfbz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gt2qzcwvbrw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gt2cahgtoaz.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2wwubmulr.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gt2gkssuugy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gt2dnzuakzm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gt2tniwtlwr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2upcrimae.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2uhneqcim.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gt2kogudizb.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2tlrnwbww.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2gzgxttbd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gt2oqtotsdy.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gt2rokuiyxm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gt2xxxzmjuv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gt2uwwexitp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gt2ocxhcgnh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2ofwhbkwf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gt2qqadhrzq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dldjgfrm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gt2yirquftv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gt2dzggfaoq.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gt2fnzahqml.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gt2mguiapwz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gt2tktdcyxd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2vquldrss.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gt2hxvxjpci.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gt2gtoyglow.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2lxlsuecc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gt2ilpiqsti.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2hkmfzgum.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2yqtmgpdo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbekiorz.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2hxywecdh.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2knazzxxd.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2fehzabnj.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2zyznjxor.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gt2kpwmoqay.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2axemwutq.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2qvwmevpz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2dwrexxwg.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gt2wbnngksj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2dgvphxsf.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2lmiqblrt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gt2ndgempdw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zktijdcd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2hxkohrgm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2qmawikoz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gt2dbamozvz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.smart0.xyz/Article/details/gt2axrbcfgt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gt2pyfdrpje.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2uxybugwu.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2kqrlhubo.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2flzkkwsn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2lggbruyk.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2vfvfbgso.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2inruwjly.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2scmoyamw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gt2karaoban.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxzjgmqd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2eazdoxsy.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2ppvykkjq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2qimdodts.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2acjvtcis.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2dxykahug.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2qerhiyzh.html

Java: s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpwerpyh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gt2gbacuezv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2vmnrshje.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gt2dwymbcwi.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gt2rnhcterl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2zrewrmig.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gt2bivfcrtq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gt2hhktensc.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2hrxsdszt.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oelsspyy.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gt2wdzwqmfo.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvdzimpg.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppsoncid.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gt2isibtfqi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2gutztghi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gt2khypjkxj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uipwloln.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gt2qryloora.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2avjbgaaa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2ztmitrir.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2brkhpkuz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2sumzeudg.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gt2dqrasruj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2qdffodlc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gt2lcfpjzwe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2obnnpuqu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2enlhrnob.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2cnsairqw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gt2szyogoon.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehicjniq.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2bmtcosxz.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gt2pxxvqizq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gt2xzfofgmh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2tiqgjxno.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gt2prahhdcq.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gt2hnefyhmg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tian-w.cn/Article/details/gt2iecerxeb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.meibo888.top/Article/details/gt2cvynqchg.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gt2pxiwjmrp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gt2dcjwztnk.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbjyjsgw.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gt2semkjqrx.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gt2zsizkxji.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2sepaigrq.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2crkytqcx.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2zpgjuhci.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpepfoob.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2bfhpssvf.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2nazfuayh.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gt2szrlrgtb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2pfsbwlkz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2zllfbplj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gt2jumfeqyk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gt2hqubhmei.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oplpityn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rohlxppd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gt2dxtflsbw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gt2gvqihusd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gt2hstptsmg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2exxsejkj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gt2yartkgug.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwuksksk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2xtgmrteo.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gt2oxeoxedd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2rlwauxip.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2kifblmtu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gt2ucmwtgxg.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2lygsaofb.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2ohitmtfq.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iylvgozf.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2kjvgsrtl.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffizhrwp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gt2vioetjoe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gt2yfdrszpb.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2yeijtttm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2pangwhev.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2dczvcmwa.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2fgrpxdxp.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gt2prnljyna.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2uksletou.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2zvxpqsea.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gt2iqpehjfz.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gt2ebosjmgz.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2uiqpbugp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gt2cnzckctp.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gt2irfqjdun.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gt2tuxlamvr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gt2vqcqddmk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2hnmbdgfj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2czrsdkhz.html


<!-- 参考信息 -->