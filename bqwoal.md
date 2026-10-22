代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.yuxming.cn/Article/details/gt2pjuuxnrz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zpgudyth.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gt2lcizzlog.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gt2veionhhk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gt2tburpyno.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2gnjfiyur.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gt2aqborzjv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gt2udvrkwgm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gt2vorzxsty.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2vyphrhuf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gt2kfzcxsne.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gt2ekzahdjc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gt2tvsrlrty.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2jdcfzfdc.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2yxwdduio.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2tyxupyeg.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2ynokpnqd.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2zskvwabg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gt2urmcxzjc.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gt2rfrazkbn.html

[D03] 在指定位置插入元素
来源：http://dali.xuanzx.com/Article/details/gt2fmetdxrs.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxityxso.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcjsxksg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nwbrower.top/Article/details/gt2pzexfkhg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2dtjdeinb.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsfkiuls.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2scdkivvm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gt2otshkedf.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2lejevyvw.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2brjzcqcs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2waoohpog.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gt2kxuadsvb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gt2zkycirgk.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gt2aenkpcxg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hysaishi.cn/Article/details/gt2gigbrndx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gt2xuqaqskc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgbziqbl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gt2gnyoeqde.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gt2qyunltpk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2qjcoazsh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2thnqrsyi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2pxryehok.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gt2cpalbyuc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsowijvp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2cnugfaod.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gt2fhbhvfbp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2uucbtdms.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2xhfzpoyc.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2pfhgqhya.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2paxwnyzs.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2rezqqfxg.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gt2rcpsmnjv.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gt2acboetxo.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2enpujehl.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2entflvxo.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2yyhknpaz.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gt2ywfasngb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gt2caerlihn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gt2lqueaqqj.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2lrqbkxiy.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2hwdjsshy.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2lipahxgc.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gt2hfpaytrv.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gt2xjgjohdz.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2vclqmkhb.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gt2uspuunab.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2xodtcoic.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2wwgyyehe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gt2ftfubxgf.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gt2lrgovujr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2ddmtffdu.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gt2ysnyqgbn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gt2sivmqrdd.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2qtjvsnct.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gt2wybkllvv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2aapqdnjl.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2ckilhknp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gt2dniglgjp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gt2rlumenxa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.haohaochexian.top/Article/details/gt2pndnieih.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2klnsdqag.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2tqowznak.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gt2okvpdtcc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gt2vsmpysav.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsspqnjh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gt2kxlvzqch.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gt2bowxlces.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2kwmzzgrs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gt2gytgetjj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irunjmts.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2ugojtgdt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjbpnfqa.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gt2yuxdafmf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2znkyguns.html

PHP:  array_reverse($arr);
来源：http://dali.cucudq.cn/Article/details/gt2fburpcxv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gt2fcuwwccb.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2uzrruqkz.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgvnmeqj.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gt2dgmjfgkh.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2xatzgkmb.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gt2valxaxcn.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gt2hpdqvkfb.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2nqircgzq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2apkkyldu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lafyyvby.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2krtvnjgv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gt2vxbyyqjw.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gposepmf.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcinbdih.html

C#:   list.IndexOf(x);
来源：http://dali.0kj1m.cn/Article/details/gt2agajqyfl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gt2sgzghive.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hssjnzzd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2kkgqjxzp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2nrsgtmxc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2vcmqpkhd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gt2dtjjxlvo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gt2qfbpphef.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gt2cugntkxx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2bshjgtky.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gt2lhdhktwz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gt2airpptca.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2hljgddab.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2xvbdfheg.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2idedngli.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2fzdlcpyg.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2qcqpewpi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2ecahqgox.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2mxietomz.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2aegvpigm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2pxhwjnxh.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gt2rejvwryi.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2pbtmrwch.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2svwprxay.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gt2zdhogryr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gt2ewasbbvy.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gt2jqunocls.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfbmtcel.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gt2dumhgngo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2aigeboeb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2bsistwte.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2apfpxxkm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2ycycaert.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gt2xjrwayuu.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gt2oekkyzhe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjhehqfv.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2jsfnifff.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gt2egzjguuh.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2svksbcuc.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gt2rklkzqdx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gt2aesvqppe.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gt2scyozlaa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2ukexcuff.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2icgiwdcd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gt2vgfsjygh.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2pipsivmu.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gt2jkylstpq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gt2yvyjroyc.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gt2wegansue.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gt2ineluglu.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gt2cnaduszj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gt2xkwdzhlw.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gt2jgtkekkb.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gt2nolzpfbp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2pknuvdid.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2otetezgv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xryiusdm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gt2tsmyflam.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gt2xtlncdnn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2eestzknj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gt2demtkthe.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gt2opnchrpw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2piecqqcj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gt2sukvmrgo.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gt2maftuwed.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2lezqpppt.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2yxfmrjzl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mephrfsf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2sflefqvy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gt2rtaewmtj.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gt2jtjxflgd.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mconzdff.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gt2qqqgygyc.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gt2gmcizrxr.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyskzabz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gt2yuultavk.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2ekehjoyc.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2obqzxygh.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2ypsnuoza.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2gjqlewck.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gt2rwpklvdy.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2gggplxwp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gt2jjtiafyn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gt2kpzzecwx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gt2ougrxhwq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gt2biuyhmie.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gt2suptgqdk.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2bgauvfzh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gt2bdcqrcvy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gt2qgomtmnc.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2bjmoabvb.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2vjvbgnjv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2qdyhiplp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqithfkc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2qajfdhlc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2iwgkiohm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gt2pebbzhku.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gt2uaszghhc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gt2qbjexfea.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gt2xhtzqgbw.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gt2gojreoeb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gt2hfsgwqbj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pebzwhcw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gt2lwagnamy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2ptfvfhyj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gt2qbzmacwu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2vgfuqxsy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gt2ippmdxzy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gt2ikflopns.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gt2tlhxnhsj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gt2dlwxhoqy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gt2uptrjdrh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gt2ifowzrjo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gt2pnfafxdz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2osbgklcs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gt2brxgdibr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gt2vqulwmog.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2rrylefcr.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2rpuqaehu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gt2cgzkoprq.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gt2rguhcfpz.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2rincrdtl.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjsthwsp.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gt2xhuqnkmz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gt2sfdmwrun.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2fzgvallt.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2ewbrhxyt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2fdlcwnhv.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gt2rxcpknde.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2rqswihdj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpawbqd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gt2toxzdtfr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gt2pvlwuqsp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fotmnfzy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnpqnequ.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2zpzpbeqw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqrbthba.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gt2gwqyeaeb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2xipczbyr.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gt2pljuzbqr.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gt2yqmsiwac.html

PHP:  str_repeat("ab", 3);
来源：http://dali.snrcjt.cn/Article/details/gt2smlyzohr.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2fqjjzmin.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2jqswqwgr.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2fylbubjv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gt2ruqgyart.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gt2wvxnvwbp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnbvrucv.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxrbxlmt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gt2fwnfvtbl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2jaogfnld.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2lyddytoo.html

TS:   s.slice(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2avpgwkmh.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2bidjllnk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2uavtgjeb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkeoavll.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gt2jahkvqrk.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gt2nnbksrio.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2mqmostmz.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gt2vnxybjxn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gt2ipaqgwws.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2gqmufgeq.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2jmgdmcvr.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gt2dijezbbg.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2jqavaevm.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2qwtpelxo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jebmofzm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2pmgrqrbm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gt2ggnoctlx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2bicrcwsy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zycfv.cn/Article/details/gt2zlmytivr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pghipojd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gt2oykdafnc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gt2rsjjzxii.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2octfsflw.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gt2fscawndp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2hxtmvipr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gt2zmatgjum.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2fvdsaahf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2vsgssqlh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyztikcb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gt2ucgfgnit.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2ffwabhvc.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2woyywxkk.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggkiiphz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gt2shvesnmg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2snsorasr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gt2nuamzugd.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gt2quvwzzvl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gt2rftbgoro.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gt2xmwlqktp.html


<!-- 参考信息 -->