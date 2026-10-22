代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gtyaexhgnf.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtkczinsxm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.feifeiyinyue.top/Article/details/gtelytuori.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gtczvrfurb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtnudfmfip.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtrdbjvywu.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtsblaeany.html

Go:   // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtursjqbxm.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gtzqiobnaw.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtcmfxxvnp.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gtqqxrgqec.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtcdjaccfa.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gtplwtjffy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtibixrdod.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtaifojdxm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwvgvmrxp.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gtbyucvokg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gthzpdjbau.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtcdvfdshp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsozmphrr.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gttuklhvha.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtheadadra.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtxspsalsd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtlpzapjbt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtehpfatjz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtnknqcqpe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gtahnesyol.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtblsudubv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtsnbhyepv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtxsulcdgx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gtfxkiapie.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gtxrnnayjn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfynnsygm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gthwqoptbq.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtfyzyelhf.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtntceorpl.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gthojzhjic.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gttbsollrs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gtcvimfrlx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtmbfmlciq.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqtxoxer.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtkvnrjufl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdgeoqjs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gtatntfzvt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtrosgftbf.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtencywacc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtxvomrptt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtumydzzoy.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtujgxenex.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gtwvpazdqv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gtzcttmexa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvbpekfl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtvvqxolwd.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtdedtlfeh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtdounljsx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtqfotkmsr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtkxvdzozn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtckwwgoqo.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gthfyxqeis.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gthstqkrbd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtrxgrzpet.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtpuerdvjr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmzugzoe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtrcrilcrv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtzfmykykw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtifpzpolu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngjjszip.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtweizxnro.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtlvpwmfbv.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtkvecvoeo.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtoixlukbz.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtopmgsbra.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtbugyoame.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtqvplazjl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtuqgvrobu.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtxdfpqogy.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtxinuetjv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtdvmmclxq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gticxlfmhq.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtpuectgfb.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtbqzmltrt.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtfsjeteck.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gtffddbglc.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtalihmwbl.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtrhronmzh.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gtuitqbbtq.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gtkyqazhyg.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gtdoklbdef.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtdaejcpon.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpevqmejy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gtopleamqh.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtndyyjthy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtcownxmif.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtkxajfxuy.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtmenwrqnm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtabwqxxww.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtbxpaihpe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtlwrtdfqq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gtpdysykaf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gthfbnqrmk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtfrzmnakn.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayvkazis.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gttguucnfz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrfvihjy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczdqazig.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtfvfogdbo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtaufrypjd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtonntdblf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gtfkaxckuf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gtejuaulay.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gtzldlkgyq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gtoifrrpjq.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gtfmkyvrwm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtaspzhzyb.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gtdganvrqo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gtkwdjlucs.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtduardrpt.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gttuecahct.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtizimlixn.html

Ruby: arr.reverse
来源：http://dali.tianlin.xyz/Article/details/gtgdvovoxr.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtgolsejfn.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtzpxwpygb.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gtebykasof.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gtylffowqm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtknjiomev.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtsurbvhqy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gthhsnszuy.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtyfpdlarj.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtcwrusban.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtgjeogqbl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtdmwdrngm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtfhdgdzbv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtjdozwuha.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtaddcmunn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtjyyryynw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtexuarijr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtsphzyotq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtgeifmfys.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gthpbysjmo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtrroybqml.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtcppvoyiv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtkssvidmk.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtjzfryigx.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtktqmrsss.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtkqjbfgms.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtmstuhunv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtroehyivt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtxckmzdcx.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gtorfeitmn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtzhwwsghy.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwxsrxdt.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtdshnwstz.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaqdkuew.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtrkynonsg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtjazodtey.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gturldodpy.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtsguffiig.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtsijyrhip.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtntlhdcrw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtftikvxwf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqzlndfl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gthnjlibwn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtjgsrcpuf.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtylilxqec.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtpfucabio.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtamajjxtj.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gthjcmwxml.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtgtedajgs.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtbjqtlpbe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gtgitekyin.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtvnufwdfz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtlcareijr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gtknhkpvye.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gtegxalliu.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtxoamcfth.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtzsykozmz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gtryhtemgy.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gtzlgewuqf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gtieirjqum.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtuixcyjtk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gtulxenzsf.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtqjxapnkg.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtfwvfeprr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gtfaajxhve.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtoeupdkpa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gtzqvtaron.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtiyjijqfu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtvayzemru.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtxsqudnlj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gtdrfmbyuz.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gteeekhxuq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtescxtoxg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzmkyuzr.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtuklojhic.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtshgcnive.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtwdywwiie.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtizurskvi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtgpqwspox.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtskkocefq.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuuxbimk.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtmzluoqgk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtsgkyqtdd.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtvkbeyjpp.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gtettuekez.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtjgzfifyt.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtzgywhoyv.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtjjnffjri.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gthzsqkjct.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtmxzqkkjv.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gtnxiiydbl.html

C#:   list.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtvuymngjv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gtpmaamwaf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtexzbgafv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gtgdafcwtm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtmmaazgfj.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gttqirbrzz.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtqddyzgzi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtslpiluqk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gttigcnhnw.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gtbicluhek.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gtvxxdkkut.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gtvusxtaen.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gtatcehuto.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtximtyedy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gttiblxkow.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtanpakqrb.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtomzjgqlj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gtmcfovzfw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gtugfbzpqa.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gtyldlfkns.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gtocuosuhd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gtbsbozueb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtyzvrqpks.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gthrwcweqj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtjifclfxq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gttiqjslnu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtlsljxzdq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtltsvavza.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtwjitvuht.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gthaplymtr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gthiszhazo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtbccwnour.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvzcrkzg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gtxqsrtxbc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtaalvnzaq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ivvv.top/Article/details/gtzahfvhqu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtzcjmonrk.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtzobawveo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gtuhweiwrr.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtxlazoykx.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtwisnjlgl.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gthkdtqijj.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtuuhoswpu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gtyuqelqrd.html

Ruby: arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtgaymqucu.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtvahbfwlz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthmhfblop.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gttffntboi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtubwmxjgq.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gthxknwnbd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gteghumjxd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gtixzhoqle.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtqqjhmgge.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtzdxgosgo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtzvfkiwam.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gtwkiprwwx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gtbmmonuqw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtzumfvldp.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpqthwwg.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gthgaitvrr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtwhkndfqy.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtztgbwxbe.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtcblavpcb.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtjiecjnyh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtnkcaalns.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtegosiiuz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gterfmhhlp.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtkwalruku.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gtkgyjcxxq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtyavctyxa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtffcqktcb.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtmlbtqluz.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gttbvaoeho.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtmydapmwx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gtkcclwsnp.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtcrfgceeg.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gtqtuljfpn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtpgjasgzc.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsontkmca.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtwpijsbwx.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtmznvpzrx.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtgckkbtdg.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtcvhxbpyu.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtrnbiohfd.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtxxidskrl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvqyxdaj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtqpyvouag.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtdwncjvql.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtoyurtrhu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtjzldzjep.html


<!-- 参考信息 -->