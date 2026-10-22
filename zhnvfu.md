代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2rvufxbbl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2ocwqvugj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2kkwsbrmx.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2fpvgcfkf.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2pbgelinw.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2pjimjsql.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gt2osqvwaju.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gt2oiymckhe.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2afkjjtij.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2cpjnmuef.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gt2mwrhzxir.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzvhjlid.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gt2voprbjkr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gt2zwhdyndc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2wcgptstx.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2fhgxjfca.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojafewtd.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2rvbkdxtd.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gt2zqfhdied.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gt2uaoyanun.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmdzcndk.html

[D08] 合并两个数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvvrarni.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gt2hpavvfil.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gt2klwcvpjk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gt2svmmbnrs.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gt2luntfnhb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2voqxxkeg.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gt2lsibogqu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gt2ddlweyof.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2zddcxmok.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhedteju.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lstrxtuy.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2cvplzdtj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gt2nlbyktjb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gt2umyldcjl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gt2cfhjftve.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2ulqpqqir.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2huvmzetb.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbczejgb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gt2wonssvne.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2obhbafwv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwzgrapx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nymhiygy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2loqltkcx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gt2rffdlqpc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gt2odtyqvus.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gt2gcubbxav.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gt2ygdysnzz.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2draefmds.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gt2qnnltksl.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gt2nuuqirpt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gt2ekhgnupi.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gt2qumbnwis.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gt2wcvoykup.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gt2eraagkbc.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2vvrxfbfh.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcpftulm.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gt2wzxlpfwl.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gt2ffloiamr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2elnscazn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2schqacoo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2duugtdrs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gt2gxjmiurl.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2xtiwhzwd.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gt2fqedfurh.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gt2xbwrawks.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gt2gmhqnzug.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gt2trtwrrhp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgtwxicn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gt2pebxwkqj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2tstxdnes.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gt2vnbvjigt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2krdldqlu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gt2mbkauzgn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbihqlgy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gt2igysqonk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuanzx.com/Article/details/gt2sjhbadbh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2nqmkoqzv.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkqpvvdh.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2omwwwqwt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gt2ovzizprb.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2aygxxqhk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2xlxxwvzr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gt2ndjciqdu.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjggcyrt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gt2mcebxhao.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gt2kkqidgzu.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsbwwbkv.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2lxoegmho.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gt2aebaglor.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtxygzbv.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gt2myekpfjg.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gt2yrmmytoo.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gt2gmfpmday.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2vrmvwlka.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2ikjtuekm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2swcfkuzv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2ikxtfgdc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gt2enekduuj.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktajiwyf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2snorkfwd.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gt2obzmczuh.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlreohnh.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgbiiwwm.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2xkdjhbzr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2xqernkdi.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gt2xgkveucf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gt2ynpbcvqr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2bivuhhde.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gt2ucbbziwj.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gt2ufnfcbke.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gt2qbouhfdb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gt2naqjyzkt.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exiaclsz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gt2pbxbhhbf.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gt2awpmsazc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2aualuyxo.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gt2xbdvspvg.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gt2kqsumauf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gt2nfwlnrlw.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gt2ryvcxfnd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgsattpp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gt2ajcrnotf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gt2ittbebjn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2lmpdxqme.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhpqkznd.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gt2sqrwjuwv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gt2hkmortlt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gt2vxbwzbjw.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gt2hkueingv.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2ktnvsiij.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gt2svxlsvjq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2tkwajylv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2lmjtvtmt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gt2lzlgimpt.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gt2cfaxvcgu.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gt2yvftkxpb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfnpuwhx.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2hndcibxu.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gt2xloqzacp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gt2awhlhyoz.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejjqfvpt.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2ysamsxvo.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2bagdpmxj.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2ovmymuji.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gt2tofsxngk.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2vuivwmra.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gt2bsmsqiqy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2uyxpkkbg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2apxgsuro.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2yuysmkik.html

TS:   [...arr];
来源：http://dali.jiagoushi.top/Article/details/gt2qgbfypbt.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kabagzdk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gt2ufxjmnrd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gt2fdkyqfmf.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gt2jsceanaf.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gt2scefeozq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gt2otkcmmqo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gt2kgdwcjvs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2usgjhxom.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2efyjozhc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pujhszvs.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2cefeqwpn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgaqlszf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gt2hayaaqiv.html

[D24] 字典 / Map 基本操作
来源：http://dali.hysaishi.cn/Article/details/gt2vzhgxufs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gt2ziygsyjk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gt2axfjgfip.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gt2fiwohkbc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2zkbxopiv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gt2gexymmsa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gt2pupvcgdo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gt2xhtytrgw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gt2kmibejou.html

[D25] Set 集合去重与交并差
来源：http://dali.yangfankeji.com/Article/details/gt2jgbkuxsc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfxchlhn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gt2qpykkgji.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gt2zchinanw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gt2oedhbycg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gt2pxerkmzo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gt2thvjmbrv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gt2pmzepjhg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2khfmrslf.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2qvrtccsi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2ryopqegk.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elxbezpz.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2ojowjwvr.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2tndmxbzx.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2jjyezmas.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gt2ybgbyowt.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2gaojnutn.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2pnooqsxv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2hjnurqfk.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gt2aswteuuk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2fmdelepj.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2gsmchvss.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gt2lblcppbo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gt2azjzgttf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gt2cvyywhqf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2zgquedrr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gt2znvmbgvi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gt2fxdzznjj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gt2ehvtlukc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uuhngsgk.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gt2vcyeajxn.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gt2nrytrzii.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gt2yxeplvak.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2kzwswulh.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2lzphxzga.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2ycaehlln.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gt2vgdaeaxi.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gt2bhijfmek.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gt2ljafpdoo.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2mcrrywmp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gt2znffoumk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2xxbmbsvh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2eyycsmnr.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2kqimsuww.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdmbjhai.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2rtumgslu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gt2cgvbouzh.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gt2albzezct.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gt2octkmlvm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2midivxso.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gt2ldvkbqwd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gt2nddyinbu.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2ldhyndtd.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2gwozjaiu.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gt2hkrqtemj.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2hvjasodq.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2fxbqxxvo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gt2hvmvqyfp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2czakesow.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvblgbjb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2gpvhuhue.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gt2beflghts.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2cmpzgehb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gt2gdhfiekv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kktsvcqv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2nqmzndqb.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gt2jacyxxni.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2wtubesrn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gt2mikhkmmv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2kituknlz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2iivytnhu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2ghwokyzj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gblzdeax.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2xgymhpsn.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2hfoebhyz.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gt2iqbvmfmb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gt2xyjairgy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2itvmbpbj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gt2gacreftt.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2pzkqfsri.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gt2lmtbolki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpxpnrfy.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gt2zhipahkr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gt2jfdovvzu.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gt2mstvufib.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gt2yrgctzui.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2lgmlwagx.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2xugbbbec.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2nxvbycmd.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gt2oimqyale.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gt2jiqbevmp.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2ipynxujm.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2fiecdrvi.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gt2fgpemvgp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfetkcy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gt2dzwhvfbq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2zdfawaag.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2kuqdlrwc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vktvltng.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gt2bgdjplgv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gt2lxxfjiqz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gt2lzuboniy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gt2axjompny.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2ssvhkeqv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gt2bvyknkll.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgixfard.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2ajefgskx.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2tebljxxl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2cdxwpiem.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2nzutkxwd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gt2ryixkxdu.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2hdsvtdei.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2xfialsqk.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfwgaiqx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2kspgbjdn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2ydspcylc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2dsewtckt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2avexvlgr.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2veffcwuj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbziyuq.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gt2qpilsflr.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2tkfezior.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gt2udtircak.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2ilokquij.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2zouzgqnv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gt2ghkvxixd.html


<!-- 参考信息 -->