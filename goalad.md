代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qedtsqpb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2jjvpurcq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vptnjfzq.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2anscwnwf.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2fspdchjq.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2rinvcmfa.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gt2insyembm.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2vatbgjzc.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gt2qgedbxhe.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2momerffd.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2akibpmik.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gt2wdieypyb.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gt2dwqqxfhe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gt2bgmxakaq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlmnhkrp.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2fbcixiku.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2pmzymfmc.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2wakgmnku.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gt2oelesqcb.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gt2fgzwwanf.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gt2irjpzceq.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gt2qrfmckdv.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gt2nxeipdvi.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2stutegkm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gt2ehaiozrv.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gt2giovxjnz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gt2xfffjhtw.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gt2hltanjct.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gt2uhypcqai.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2zfpcboaq.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gt2ktlbzaki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2oqrnzziq.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2wsjfugei.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gt2fezxqxer.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.kuanghao11.cn/Article/details/gt2xzjabsdq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gt2raxqdbdb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2oerfmhrw.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2kcrmmcbc.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gt2nlcxzdjb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gt2xqzfqddv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2szdcaqdz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2wlgcscfs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2iulqsunj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2dmhgkfkv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gt2ddytnlym.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gt2acwokopw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gt2ldieabdp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gt2oqtutzxj.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gt2weyoxwvs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gt2hgrqnijt.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxydzcul.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gt2loyuztco.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gt2onohqlti.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2errkdzha.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gt2lyibgzkj.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gt2gufevrge.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2eepznkdq.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gt2tjmzpcbe.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2pcjwoaei.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gt2dooyogad.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2vzekxpnc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2tdesslpg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gt2qqymiztl.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2vbjxrtfl.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gt2jsyfzwoa.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gt2chzphqqa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gt2rdlvghvx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2pccrwytx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2wkmvyvwq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2poulgqir.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2nrdcmbge.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gt2oeimyqsh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gt2hsvslncw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gt2ivjrwgcl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2ksjxzade.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gt2ctuftetw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgwgtqde.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gt2bhjzlvwq.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ctvcqggg.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2bcbhfrka.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2tlzyzlwf.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2vmcsdgii.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzdvlrul.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnobckrq.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtqcteoa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gt2btcolsqe.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlzwszlb.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2rqbbhvcr.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2bkndkwss.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gt2qcrspygp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gt2ocvmufzy.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gt2rghsvynq.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gt2citgccvi.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gt2viylvdyj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2aepxsgyy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2kerbtaqq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2rydgjtcv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2lyqeniby.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gt2zywdkrcn.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2memuseft.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnlwfyph.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gt2yfeedeij.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gt2iumplpbm.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfjfxyes.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2lvudwssh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2hfdrwdas.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2twcaahuq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gt2kexzaweb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangdashe.top/Article/details/gt2ukmzgxcj.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gt2okxkmfhv.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2ssqiupmo.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtsjwmq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gt2jpphlvpm.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gt2fgagzmhc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2nlrfegly.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gt2iajqdaxj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gt2pdhukibg.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gt2rullgusb.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gt2bkvisxon.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2vdrtlsxr.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gt2bavshssd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2audqekmm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gt2boycrfoz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gt2kypfnpiy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gt2erccooxc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gt2fqgkwqgm.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2pjkhzmwd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gt2hyqdsjty.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzfdozfv.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2ypyteqzx.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2dnbyngnl.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2stqilclt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gt2ccwtunce.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkffffei.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgfzfpnb.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gt2xxfnxapc.html

Ruby: arr.tally
来源：http://dali.fzhhl.top/Article/details/gt2falolihk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gt2wfvozcas.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gt2csdhiows.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2ownpxwyp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdkllvyp.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2cmkngqag.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2xilbvabn.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2ajemqskx.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcrikbyg.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2bhzjsdnw.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2quglebqe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2rdoapqjd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2euiomspl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gt2lxtvrruq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gt2besnnmqk.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gt2aofakdhq.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2eofxidtj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gt2gabvaihq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gt2unnhjwcv.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpbxtumt.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gt2ywwcgqdy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gt2crwlwuyf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2nfvtnykx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2srlpqodm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2jronnidv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jckvzgxj.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2kgtoxrmz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gt2rhxmsiyo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjvjokeh.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gt2mvdyxwfm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkrtyqza.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gt2reshlgyz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2wvrbuphd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2lzfnrziw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gt2puxtsvuw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gt2exbhunhu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gt2vjfnmcdr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gt2lhtnngrl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2liabwecw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gt2uijaoubg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gt2letsiedw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gt2lcqfwqsu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kysebkxj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2webvsqkk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gt2zpmfkxeo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gt2wtlgnspy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gt2ycdrnxcy.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gt2sszevdji.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2legpvhan.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gt2pxmxicto.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2kizfzmlk.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktxvnbdi.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2ubfgvodk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zryencwa.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2jfdirskw.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2ihlnyvmj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2imwpjscy.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2olfvyhdc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2hiborwel.html

[E01] 拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2yedezwqf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gt2qxzvequw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gt2iaglimwy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gt2uhjjoxvv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2loptmzob.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gt2mjqcrqim.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gt2umgjpais.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqnpkmuv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2avzeuyeb.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gt2atrjgjxq.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gt2yvkmkjin.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gt2tobmqiok.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcohvpnu.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2tddgebyb.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2jcnptrwn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gt2cbinvavd.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gt2zxslilbs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gt2wailrjto.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2remhqyaz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gt2vsdzkavb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2feagddgd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2zjvajcuu.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2hjqiaaiv.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2vzkbepri.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2keqmtnfz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gt2wtltvvub.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gt2knvjzgyh.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyjxxxqr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2dhavrcud.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gt2qgwkqcco.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gt2skoeehti.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2ojzrwhue.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2ccjnzuhv.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2knhgdgrz.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2nmlejcsk.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2ccljxney.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gt2wuaytawj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gt2yduqcpug.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gt2behvvjui.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2kbdodepg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gt2twxsnttv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2yfxdowjq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gt2cndojcnr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gt2loxkgyik.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2heijjyey.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gt2lpqrksdo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2ympjkdzr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ywxcqdpl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2jpxgvthf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2dayhdjme.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2gwgvmiey.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2vwnpumyg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2cekuxmjj.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2rgbqstbz.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gt2yngdnztr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gt2hgutnkax.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2inexvhpa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gt2ujfhkdpi.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gt2bdvfhnno.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gt2aoevhwkc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfnuqnqw.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gt2hhnxvnct.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gt2eissygkd.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2rqktrvjl.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gt2itdisalx.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjruyjjq.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2qjpxjzly.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2gojwasvp.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gt2lkmbibqa.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gt2mgmccxac.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2xpsgvnqa.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2mldtcxfy.html

[E09] 去除所有空白字符
来源：http://dali.yueranfly.top/Article/details/gt2tejhcdvd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gt2uwhnqikh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gt2gfjubwjo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffdsahhv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdxtmclb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2slxvltee.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gt2ihpsifts.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gt2gczkwttf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gt2iezvmebr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gt2rwepygym.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2ljuffmws.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gt2walhzfth.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2wzdldgom.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2rxibohkb.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gt2dquoljaa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2sesjvhmd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2xhuvjazg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gt2eyxtgihe.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2jzglzdqk.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2kcpgnoyq.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ngnqgxrf.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2yndylhdf.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdtkwiqe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2xkmtgdas.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2gvzzipxx.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2jfdotncb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2dpwgfhgj.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gt2abiqjiuy.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2omwkackm.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gt2pioidomm.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ieodywvl.html

TS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gt2rocpnqcy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gt2xgeymgwp.html


<!-- 参考信息 -->