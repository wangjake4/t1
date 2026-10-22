代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gtklsgbjfd.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtugsjrypa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtnbpujwpx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gtyxpxizst.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvebepmbm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtxtfhppze.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtgtbkxgrk.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtbvisnpet.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gtucewgqwi.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtjuzdryew.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtrcgkpwuy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtytouxffq.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtxpoive.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gttnrdgjfq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtplykqjov.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gtdxncwrfh.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtieuefvfn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtdhzvroia.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gteafblvyp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtllxsddqp.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtotiebcvn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlfxeepll.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtdgbskpqd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gttasqkqhj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gtubbhbcek.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gthuhmpgjl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gttqlctagr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtbpwcvzmb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gtbyljzhxa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtvmxwwqsh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtncjczssz.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtcmjzugrr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gtbfltipgc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtxhasjvey.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtpyqropni.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtlrifdzqz.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtqxqzedum.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtjpdzsvpj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gtxurbubco.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtzljljoom.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtjrvxbxey.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtjiralefx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvizehwe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktattqxk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtytqblauo.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtqvgurtcr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gtfqfhihfr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sxryk.cn/Article/details/gtfldnhvoo.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtsfzelmjj.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gtrexzepav.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtgktvshfq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gttyiqtzlu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gthfzlxbnk.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpgbjgja.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gtnachdoyp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtjolriqvk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtllcdmqcp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gtamnszofs.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtqsmbrcvy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtzesfwudr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtakjiwico.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtwdhutaca.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtnvvcyowe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gtsxgmstoj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtocwtrhto.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshbqeiap.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gthxmwwhpy.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtspdlloas.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtmjooxnex.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtujjdpkgi.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmumvosgu.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtlqnqgwws.html

Java: list.size();
来源：http://dali.tanke756.top/Article/details/gtvdywcdcs.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtxixgetin.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gtumvkfjzv.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtgiwjjmzq.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtphifvgso.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gtbfcanqzl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtelokrolw.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtvqyfwzdg.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtvgtdmzmt.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gteuyrmfgl.html

Go:   arr[1:4]
来源：http://dali.aibaodan.cn/Article/details/gttherfcdh.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtpwowfvmf.html

C#:   list.GetRange(1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtgxoorhso.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtrlhbxykz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gthwurxpyx.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gtfwseagpv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtyckrtzlt.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gtygnjdbvy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtifwxlvfq.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gtijzzbanb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gthjkttsrp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtubrjwbxm.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtoxdsfknp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtkpcvyvnm.html

PHP:  sort($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmgmxnnb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtyaprfwcb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtaxzlzery.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzvfrjpy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtzrkhhczl.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtreloopzn.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtygveistp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gtcmrzljgs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtkllqcadt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtvgqsoexy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtxwkiojpi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtjrzekftc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtssfaxfno.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gtkrvymvif.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gtpclzxkqr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtamhkflmg.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtrvhuxspa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlprfwsbh.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgswsrcp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtxhfwmgoc.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtggmpsblp.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gtgjakbssv.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gtviikdutj.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gtgeszoceg.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtycmkoeas.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtastmmghi.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtsernixec.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gtlyuawgbt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtjrrculgp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtxefijqyk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtcnzgbnph.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtylhvwwce.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gtyyobcxoc.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtgoythqgx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gtfcwnxfbj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gtqztniujw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtxczzkgss.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtmumvihvc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtxlqzajmj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gtqusynqtr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtalgumeze.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtowafnlot.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtkjfwkukk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtgwajwipl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtpqihonql.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtvlekbfzs.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtlxtvjlkd.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtlcvgvykx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtamuwzrzc.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtbirspxkf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtxaqonqdi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtpwdvcsbn.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gthhmwwvqx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtxpsczpsl.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtelymrokt.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gteyjzwrbk.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtdfunbxof.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtxxjchuzv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gtdpmhmiah.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtxnegfhaa.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtsaboelam.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gtqrlrusod.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtvufceotr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtvbwglckt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtkvojcfmb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtdkhajywh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gtswfubmmd.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gtpumbmlol.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtiwirbafh.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtcarnzott.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtddveddft.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtghjoswni.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtczvrqmgw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtilwqrigw.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtrejfulpx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtavixvrcm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tanke756.top/Article/details/gtjdhvltwo.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtgmbxqqgs.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtmtbnamgm.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gtkedszkyd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gtgujbivaj.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtwrwpmfvd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtiorznfkb.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtyipirqyx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gtrjfaoirn.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gthlxccnsn.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gtvwuqijkm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gturceouad.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gtuvsxflee.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtwdfyvuev.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtgmchcsfs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtlpiojncc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtrqacmpja.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gtoonpnuqv.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtqwubcfmv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtshhixviq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gtfokwbrls.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gthrlavcua.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtptqxumag.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtiulfvnvz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtbamfwhyg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtyhpwuoal.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtmqrhwzqf.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gttuuflwqc.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gtinxrwwsu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtidwgdogf.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtvaozdfld.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gttppgvbdq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gtcgtwmotx.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtwejggklk.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtozpfwttc.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtpljtgyaw.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtvxouvbat.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtvtplkifd.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtdgjetxgv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gtwsrofoof.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtzlyxddtn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtkcvijimz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gtogghcllp.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gtcskujgtm.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gtbepxomsb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtrriynznv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtftxhcsav.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gtclktzuiz.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtjhcyhdst.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtyhhnzakk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gthjveyxtk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtamcqhera.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtosdapugk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gtflroeqsd.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtfajhvdws.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gtcyevgwie.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtepeeogcz.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gtrczunlku.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtbemmtigi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gttzzflsia.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtxohtwdkj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtbxpcfssl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gtadjvbymd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gtnhhydala.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtqtdwjbqd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gtryfotsut.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gthlbxhdbx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gtazxyhgse.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzijzdwwc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtruxzkalk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtlzeyjgpq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtyyzgomfa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fzhhl.top/Article/details/gtenrslpah.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gtddzkjizi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gtftxfaitd.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtwdsnbzkr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtsorljzwo.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtwuzdjsuk.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtkpkcvvgg.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtgflpfvmg.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtvhyhiiiq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtfwtsijrg.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtvwhkoxno.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowhbtigh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttiryzdpb.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtqfsahvba.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtuqlosgko.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gtnjvtymgx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gtipoywlxw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtuptqlihq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtvwaerdmj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtclsnqpzv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtbeuzkezg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtooxpndnt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gtzaxkydco.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtyrbazszh.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtlzmatdzi.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gthpncnjxl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtzdaufubt.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtfbhabnbe.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtpachkyvj.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtxxeuoodb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gttljaumfp.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtxlbbando.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gtrzpxkhec.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtqbwuciyu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtwvvwojbd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtovqcqhza.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtowypewve.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtdbwffibx.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtrfphrgxb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtokklxoon.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gthxvbscbs.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtdveqheyd.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtxzydqukp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoigmeyj.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcuclkgr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gtcqfgzaox.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gttinlheov.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtowoxtobn.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gtrqbuplmc.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtucbyualb.html

C#:   s.IndexOf("x")
来源：http://dali.sweek.top/Article/details/gtkrxuxpup.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gtbeatdoab.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shzxlz.cn/Article/details/gtiizuvooe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gtvndyuvxl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtpqjpiael.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gtgdekqtrf.html


<!-- 参考信息 -->