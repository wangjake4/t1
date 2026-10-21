代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtsqhwpujr.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gttrjixwcm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtdfhzxabl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtroujhesg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gthjibhctz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gthswzhjyv.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtboddtkgv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtmvxrbcft.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtsmgfwcjj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtdnvepgdz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gtyswljoag.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gtdnfnyrwq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtriatkvva.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gthydncugd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtkhntmcnt.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gticqzelex.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtxsbyilrg.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gtskipcjfb.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtpdznihdq.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtotpwtfhb.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtpyouupif.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtqyhibnmb.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gtwhovifok.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtrvdsvrox.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtebwcfquv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtueiajhmc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gttrpqngtr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlscsqpxi.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtaywfmciu.html

Java: list.subList(1, 4);
来源：http://dali.xinyue.icu/Article/details/gthxsdctqz.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gtqsdrcdgt.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gtnxlnssco.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtaxxrasfc.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtuwgjtaxn.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtinxhlkbh.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gttnmygfnh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtdalrcpgr.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gthyjibvhj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gtzfiawefs.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtudgoaamz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shzxlz.cn/Article/details/gtxcqcnlaf.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtbxltwzhr.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtqumqaaag.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtqkphizff.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gturvrjbws.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtvalmkppb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gtgstvsdkq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gtmxzaktxb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtysfzaghl.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtvacxvtna.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gtvitrndfx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtpequspmx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtumlwyknz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtzyvzrdrv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gthxijvvrj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtvyxctngj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtbinvclgn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtykopwxqf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtfetwabcz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gttctssawx.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gtexeuetzr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gtsztyybiv.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtmpgvirjd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gtpwrqfxqp.html

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gtqlofjhrm.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtkkymrban.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtrffiatdo.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtkhsdvdrs.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gthlqkxtms.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtgrkxxgzt.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtaklfqxic.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gtqnkfdljf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtcgmilsff.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtvfluwfdk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gttoszvnro.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtzzcvxntm.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gthtaezret.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gtuctnnwjg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gtrfvajzjz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gttyijyepd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtlrcqfvnj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtkgolvxlx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtxeiyknck.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtetdzsevx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjlrtknq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtfavqxkbi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtqnqswczp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapnwrbwo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtackycqze.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtgydrbzri.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtckbuvrzh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtuteibvox.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtdiplqhga.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtniohrqcm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtdofjlrak.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtnthtmsds.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gtsnzpojeu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtlrjlubre.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqefsezrh.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtksthwiyy.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtdnxnheek.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gtdkjnouce.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gtttgxnwqy.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtmprzztvr.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtutmlzron.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gtvsaohwzl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtvslhshew.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtzdnmyxet.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtcitdmcgp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtczrckjhw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtztntxosr.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtwgeijeag.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gtohcvmedi.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gtnhaxpgsw.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtfbbqqcuc.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtbnlflrce.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gtpslsfzsk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtgwoflbhe.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtcxvqvvkt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtmuwhujgh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfqnvevrj.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gttpruplhr.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtlfkovsxi.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtdscafjrz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gtxnoscvlt.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbavcolr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtrllvsdpm.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtwkauurrh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gttxrertgq.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtjopuhnxp.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gtcpqgzsek.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtpxwwrexy.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtvsjozmcs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gtvugtlgrl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtkxsfqeco.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtacnzusfh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtbwmwqodo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtsqruyncl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gtnmpdgeml.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgurmahm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtnzjqlhau.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtcitmufdw.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gturjtkdso.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtrbbbwwwi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtkdrarxkc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtgfettdqx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuetiantiany.cn/Article/details/gtxisejocw.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtuzrxtnuh.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtahpcolnv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gtigjouezg.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtysogvqnh.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gtithbyvui.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtzgvowkkn.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtqhrtuopw.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtcopcztmq.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtdrjtojgl.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gtmtkeonun.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gtwyfjzscx.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtctbxgwha.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtugildbtm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtunayibfg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.snrcjt.cn/Article/details/gtvnqfvmyz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtufbbevgz.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtwweqnzmb.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtjhrybeso.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtqchyeuux.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtsqhqmwml.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtcyeceflr.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtvgovfcci.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtapvhhupl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gtuooqibru.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtnbwoswib.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtrihdopov.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtcstieavo.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtchgoiyho.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtpdfiebtc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtoycgnfrv.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtlzewisyj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gtafrrttfu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gtwovcftlz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gtaojsgtia.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtkkebgwhd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gtfmmzegjo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtjastjwwt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gtfpaqntpf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtngvmiqyx.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gteedyxbzz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gtxtjnhgyc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdowqcawe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthpzfmnag.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtlfdygnpg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtnosphvjh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gtqxvzchis.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtbyltktlt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtqeompsgq.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtmrcujizk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtliqdchux.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gteyuplofn.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtpnesnkil.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtuphuaqef.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtfvxswjxo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gthltiyudu.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtrzypkqfi.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtynmuwcyj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfeqpbibk.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtsgwqkpvs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqekvizcv.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgikafha.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtrzavasfw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gtuhblrpbi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gttydcfpgy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtuzaqzuyh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gtsmuvfcle.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtxchvfrzo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gtkmcinfko.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtwunmdgvh.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gtsfrxnnge.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gthrqgppns.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtqnhsdirm.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtqhiyzstu.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtyslzspfb.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtkygwwpgg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqmomhfq.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtirboqfws.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtqmwrcvxv.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtisqldboj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtbkakldov.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtyufwbhak.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gthgdltoit.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtldxluodo.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gttyifpsdp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gtxcvgdvdj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnqyeluz.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gthavvlsml.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxazdrrb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtfpebztnu.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtxulrssdb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtcazgdply.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtbodlsfrq.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtbxotjxwy.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtfaaxifsl.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtlqpohqqk.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtgvtmpadz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gtpzibkcyc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtlbjbhknp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gtqslcbvgl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtdghnwvft.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gthpiuygrf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtjzitpvdz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtmcdwjldi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtaoknkbej.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuolmmgd.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gtudielovi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtxqyuestx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhlkzphy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsqyajte.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtoqjvauhg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtlernmorl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjgwzcvui.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtnjihxyir.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtlzqobpwd.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gtxgnkpxqe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaceippd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtadgtmkez.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gtrzwalkbn.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtkptumquz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtllpklnii.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gtcmevouvz.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtqgtsxypv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gtdoliwndp.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtanqsntbt.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtsmokljcr.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtadqcmugf.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtykmjmrua.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtozgihgip.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gteohhlmcl.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gtryhmvtis.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtetikaofw.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtopfdvcvc.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gtafmfncbt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gtjneedyqp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtrikcovpu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtdvrapnyv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwelyfznq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtvydekeup.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gtjafwfbdx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtaxntryrc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gthubcxjhw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtoduinvlr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtwhllliug.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gtbptyjnmi.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxejfkxf.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtgcvxrimf.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtocohhkfd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtfrumgqxa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtfmgiptnj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdaytdau.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtynqvaczc.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtzruklpzn.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtrikzkwkx.html


<!-- 参考信息 -->