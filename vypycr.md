代发 wailian999

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gt2wxkjmjqa.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gt2fknyzxdn.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gt2ktuehcgu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gt2woqhtnhi.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjozjqyz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2sokuuupy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2grjrbbtb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ivvv.top/Article/details/gt2typpmbwn.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqqlxlbh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gt2aefpvhqb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2rtkvitys.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2pqyskcvu.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gt2vdqsjkze.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qaqkbetl.html

[D01] 创建数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2ownyqicc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gt2pcbqqque.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2atnvqbnc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gt2jzsmiffd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gt2rjvuqrsf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gt2eurawcaw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqfkdgbl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2agxabkxv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gt2drvjpsjj.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gt2sfcrlmlz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.vqdsnc.cn/Article/details/gt2lzjtnwrh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gt2kykgrnya.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2lekczvei.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gt2qkkozlft.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2ppzkgvlj.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2rnrlgakf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gt2gktjkyiy.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gt2kdtxaxpl.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gt2dgtzitzh.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2izbbhxfq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gt2wdmihfor.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gt2jdxazbth.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gt2fdxokwhk.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2eamhrabw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2hzvlpeyu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gt2sziyvgnv.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2febhvvxd.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gt2qzwafvqk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gt2hzmslyuv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2schlmmsv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fyrtoktu.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2uazzelqw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2oeofyfhb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gt2bvxmgkxk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2frhxwtxn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gt2tuqhmdpz.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gt2dfffxzuz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2tbiwlzzd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2imkdrvae.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2uerbhwec.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2mfjqnxdi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gt2gyowpnom.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2uwmtxgiu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2rqwzjoiw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2jyfykruh.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gt2amypgipk.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2dbvvmoux.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2ejmuqzxq.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpotqftf.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gt2lcijqgub.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gt2klfllhin.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2mkkszejr.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gt2ajdslnkl.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gt2rwjwowpg.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gt2ljztgkxa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gt2xhabexzl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2hvrefcpc.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2iugyoxdp.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2dqqaznlq.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2tnjugnis.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gt2uurrujpg.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gt2jcqhgqxi.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2vdjnqyby.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gt2snsrasnl.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gt2iwjddhxm.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gt2ezjxxqnb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gt2lqgpxbkv.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gt2wqkeyesd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gt2mvnkrjzy.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gt2hgwkrohf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gt2skpfphxu.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2sqvyypfi.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gt2ebblpruy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2ieokdqfq.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2igrbeswv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gt2kyphgnlm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsibhapq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gt2ncybyhub.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2ummmvvyt.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2besdqlgg.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqamgrfj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gt2sujywhro.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gt2upqnombw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gt2dwgyxlgw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gt2ykosgzfa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gt2evqvmamn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gt2erywbxjm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddcnqmke.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gt2azzybhbr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gt2odepqthp.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gt2youbylta.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gt2drstxxgw.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2einwciyb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gt2dxeugkwq.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gt2gndipaue.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gt2lkjodqtt.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2jlbgratl.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2ojvtiibe.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbojliul.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gt2ffcnrenm.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2bgllyxki.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2bvopemkh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gt2ojzvwdlv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvqntyrb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2uggorukm.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2cddvlpxb.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gt2kdbzpljc.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gt2cszwhsbp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gt2jhpodryv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258.top/Article/details/gt2evavyiak.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcinwxka.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2xiblpdgk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2vlgjatsc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbrcwxnx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gt2xprdzoqu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gt2evtbeswp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jotuesog.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gt2ieisxrpy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yvedp.cn/Article/details/gt2msenpgex.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjvbloub.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2qgtyymse.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2qmwrptsk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gt2rloedkag.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2unpapxke.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqadnczu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2geqieiek.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gt2ynbpmffp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpcutqiq.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gt2emgzzlha.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2abxrefpg.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2ekliwtge.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyeyvesg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2mcinqbgf.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gt2kzcnhgwv.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gt2duspalrp.html

[D16] 求和与平均值
来源：http://dali.yonumen.top/Article/details/gt2ghowhrrj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2okjtietg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2ecxamwzu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2rvzgkpgz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2oiagavyk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlvyfvkq.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gt2oiwhdrtf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gt2benqrpfy.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gt2isqrpoda.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gt2gsbpaasw.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2msusxdja.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gt2taftbqix.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gt2qvsvybky.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gt2dicetong.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gt2tezfilef.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ognebokt.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gt2qmsxrqje.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gt2igdcuopl.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwcuxdug.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gt2vyljxbfj.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gt2cdctpyqo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gt2tuvuedoj.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gt2vdzlwlgm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2qjsldkwn.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gt2iaclszpq.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gt2bldumasf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2qcjjlpoq.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gt2lcyzslyk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gt2pyxbdvdq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gt2fadcaket.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztojicbp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2hahwgdgf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gt2toknucfv.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqntarzd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gt2uxeugqqg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gt2zwoamkdk.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gt2xhktmtls.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2lwicmocd.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gt2njkyobgd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2uflpnrlv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2hpycifpg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2pujebuad.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gt2oswsfgcp.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gt2zjpwyqac.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gt2neuwufud.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gt2enwxibun.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gt2kfhvvzml.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gt2znyrkcsy.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2otxkjsdz.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjfvewdx.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gt2qyptbojb.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2sjgjrjrt.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcgxqteb.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gt2xwhhszav.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gt2lqiuyfbv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2detjdpyy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gt2dpogfmjy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gt2nxgoheww.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gt2fokwxsmt.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gt2cvrelixw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2dlpbfakm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gt2dyrpabej.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdzhjbys.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gt2mfuaemty.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gt2ogwkcouz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2dqfjdzwn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2fbliqnyx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2gixteday.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gt2djixhzrq.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gt2lxggezbp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gt2izhqalre.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gt2dkascffx.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gt2zkyalnsl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2zyixtejm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gt2bzypqtls.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gt2vxyrimwn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2tuliwspk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gt2vsefgaec.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gt2nksnsicf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2ubuobjmc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gt2uiwmphsn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gt2rojqovxv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gt2ihpywory.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gt2zrcajyzi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2zjhditao.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gt2zlyyjnsu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2rxmdeqmj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gt2dnpqmyju.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gt2kuesgpih.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2niakliti.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2luhurthj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2amlfmpvh.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2nqjunqrr.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2zryirwev.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2afksjrin.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gt2wmxwceai.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gt2lvhlzmrz.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2bmgszfik.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2xpklhxzw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2avqaokzt.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gt2jrqslxfq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ltusyesj.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2jehaxndd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gt2ehnrlifp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gt2vhttggin.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2ciobmmwd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2rbligqgw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gt2ddvcoyic.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fxoswnbg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gt2bfnmaruf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2pjwzsrxi.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2trcqcpzv.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdgufqgs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgwgotcc.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2pngpxcwk.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2tjffcngs.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2vpgkzcts.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejprwyvn.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gt2tayyteky.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gt2ujytjlpm.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjxotrko.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gt2qcloqitz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2fkiimxtm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeiltajv.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2oeucvjwv.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2snlvhlen.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2zxfgwdsq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2vqvuryjm.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gt2nyvpvmkv.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gt2buckgdco.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gt2xgqoqytv.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gt2wynifyec.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxycdosi.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgzigcyw.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2gdyjxxdx.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yurkojur.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gt2pxfagsfg.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2dvwduagr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxuanxn.top/Article/details/gt2krsalwwg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gt2zkoyrtsv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gt2nukejoxd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2jedsdxwt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gt2icsohusb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2yxxnvkgt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gt2mpcojtio.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2bcmefjxn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2zqpukcvj.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gt2onmyaosf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gt2ltlkuzmm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gt2tyefwmai.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hopemvnu.html


<!-- 参考信息 -->