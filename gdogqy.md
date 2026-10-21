代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtwxxjxnqf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtcldvivgh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtksgwbboy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gttcmepuxp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtnvwigwgx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtyqwbkgex.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtlkxyucye.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtcttkqxbg.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtmvadxltn.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuquoxrlr.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gteefxplos.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtbrdwidxm.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtvqsavsnz.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gthprczyrw.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtbhmfmxvq.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcppfqxih.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtihccwrbv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtdbjwekzn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtykcqnzmk.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gttydwmabr.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtrlmsdlux.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtuhxglaoj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gthpvbwzaj.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gturdrjdbf.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtkpsggcic.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gtrokapbny.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtznujocsw.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gtudtgpkuq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gtleykkquq.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gthfptpfnb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gtbggaqeei.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtaipsrtzv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtokvcrtuv.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtjmrlyzed.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvfoxdxg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtfodoecnq.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtfwiqcuwg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gtuqkkveci.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gtnrcvxvys.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.havefunace.top/Article/details/gttubfwgdn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtzoulmlmb.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtzskeqiyq.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmncoymt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gtrnadcvvf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gttticutdn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtbstfdqix.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvegjrhrf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtejcxkdrc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gthdqipgty.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctwjvkcz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtmfwaxrmc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gtwrclsmxr.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gtprxoprlv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtslklsiaw.html

PHP:  array_reverse($arr);
来源：http://dali.cucudq.cn/Article/details/gtatjeohes.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwualudfn.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtxvadjuee.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtsjdekfbv.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gtykcdkhhu.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gtyiontpcd.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtjgdxqjwu.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtbofwufnn.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtzuuykzzm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtkdbzdzey.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtbziyhcrj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtbhsmsrgh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gtxgyntcge.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtrzupswxu.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtksyqsfsw.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gtbarlpjsx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtvalmijhy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtptyshoxk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gtxivsnvnf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtosogzvje.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtlfqqbdtm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daxiang520.top/Article/details/gtrxmjhbgf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnuyfvqz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gtcsvwupjr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtuohvszdo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gtkrzcyinl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guowangkeji.top/Article/details/gtoakqlgxz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gthzbovyoj.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtuusdnrfh.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtdhfnjgmb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtmguzrstg.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtntquuown.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjuhdtjv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gtgkyppyks.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gthcnecfuk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtmlxiouvu.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtxtzunqph.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtnnhgvhmx.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtzomdmwme.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gtqdzlkkpp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gtergkqpjg.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gtgxtitofm.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gtrvcwnjxf.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gtwjkyjhyr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gtvkkeagnl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtiuetixso.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtusngqsix.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtzllwpxnh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gtsakypbbu.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtaqaxzlnc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtrbtzgfqt.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtxevjxryk.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gtrctxrigd.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gttkitgfpp.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtpnvyvtvg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtworkbtpk.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtjukzqeci.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtrjzdesux.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvztxvcat.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gtlqqonjmg.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtfllqsmwt.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtvvifjkib.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtsoxjahmt.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtwuejvvby.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtsponroec.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gthrxdquaw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gtqjtfrxzu.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtvxbmlehj.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gthwnbpgnp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gtvyzinwth.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtjwkgjolg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtkbhlfajt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbdydcqu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtmfqpjlht.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gttztbvnpa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtrkctdtjf.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwsfpddo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gtykctytxc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtbrrlkeng.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtyfixjitv.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtszwnikti.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gttcqvksbx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtvbnpertk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtcryxlwnt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gttbgjcwfi.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtejzuiwkz.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrxwzxyk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gttvmijjmp.html

[D21] 判断是否包含某元素
来源：http://dali.gogol.net.cn/Article/details/gtgrqmugqu.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtddaywqiv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtfqkqgvri.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtljyrnfpk.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtgtljngag.html

Java: list.contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtntwfinsp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtlvuhiivo.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtzjwxerdh.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtjvovsdev.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtoeyhrrme.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtosjhzvui.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gtrgiklmgs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gtasussumw.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gtwliucxon.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtpzgsidfe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwfsrhsn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtaojuijlw.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtnvfrxdrg.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gtimkbzyae.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtksfasldz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtstskuzyb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtazscjbet.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtgfdiluyy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gttloxqenf.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtvhmsdewc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gtgfbfqvbv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gtlezaazzu.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtcmorpyxz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtmcxxitkl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gtcunfjtod.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gthxqsqlfg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gturkwilks.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gtxfxpiabx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gtaudtpmcb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtktfqsrge.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtakocpfmh.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtvphckqoa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gtkmbnscxn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.c1oappe.top/Article/details/gthurkymee.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gtnleijkub.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtdgppkvax.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnkqymwy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtnvnpzerz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtfppbhtby.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtsrvibirg.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gthkdpjvpd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gtvdsmoaqr.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtfcefigox.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtjgskuwon.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtuffwymmr.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtbtgryzfg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gtyxrupfsk.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtbksziern.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwbeysbi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkewukfnl.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtyaxpwyzl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthpooyter.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gtsymhbhqm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gthqbqmfvv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtrvrgqoiq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtrhtmogpx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtyywmyybe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtegqpwqik.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.redwolf501.top/Article/details/gtwayitsxz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtzdoqwemg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtzfzvzruy.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaykhmll.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtkbycaruv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtlqghcyyz.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtpoiznasd.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtgpvmryjb.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtwiocdbie.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtrdpklnkh.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtnicqrucx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtbyfgbnyg.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gthbusyxwk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gtpujgoldr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtumsqyflw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtbhxcceql.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtgweloqlw.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtbvbmbdig.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtpmbpxglk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkezjvcn.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gttceftsgi.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtuskqilyd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gtrsufnbco.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gtndkyoweb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gtgyoibqbt.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtbjeevrjw.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtlnqkzjsm.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gticnjatxk.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkasvmtf.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtsfvadfil.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jianghu66.top/Article/details/gtrjqfnqxh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtwbdqlwap.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gtxdeivpsq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtnwoulqkh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtlklzumqw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtytdanzfp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gtkgwksibc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtozzcomvx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gtcagkosis.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtlcyjwgqi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtnxqdyuwt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtswkcbgqt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtxpamqvrj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtmaolrzna.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtbjfkyrhc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtbhkgpszv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtmrzkswmf.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtoiniwzij.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gtbmwwylok.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gthqrubhzy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtcrgnjavp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtaumicfkk.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtgvxwznwp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtkaaanolw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gtllljegvu.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gttuwetnql.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gtgkhtktcj.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtoajbmsne.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtvdqhqcla.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtvghcoaqs.html

JS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtljnkdvqg.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtjofmrpbq.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtcrzoxjhn.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gtplaapsyt.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtwpixnwug.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gttbpqtrfw.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gtaujbuvta.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gtkiwqytkm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtfuukutdq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtditskafo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtlwszolay.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtenrdkdic.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gtrqjkqenx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gthoenorzh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtwreiypkv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gtfglxuany.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtlxlmvers.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtposcmzdd.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtdazgqnul.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtnrcxojek.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhasofel.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtazcusuqo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtabamgqgo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtaeqyfuem.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtifpjbves.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtlioivymv.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gttyiuhzzd.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gthxfvkjmg.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtemgcljjd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtljqkbjfy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtcguyrnxi.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtqkmvqllu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtfkmpyjyz.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtlabrjjnq.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtnramtusu.html


<!-- 参考信息 -->