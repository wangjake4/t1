代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2danrzcdr.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gt2xkdkryry.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gt2cqpmiorb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gt2irggvgvi.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gt2ovxqofqd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gt2qxzfucic.html

PHP:  // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2lfflznlu.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2fqhcoyqe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gt2tgmnzobu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gt2mhfjjwsd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gt2tazxifql.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gt2psikxyri.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gt2evddhikg.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gt2yoedwivv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gt2qnvmivnx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gt2vbnzycew.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2slutxhqr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gt2kjejlukg.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2lellsykn.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2jcfjlnky.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gt2znycjqes.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gt2muecrzua.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gt2ewqjwqsl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gt2psyjrolf.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gt2chszvlab.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gt2azwxhlji.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jiagoushi.top/Article/details/gt2vfimrdzh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrwkmaxh.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gt2wnjymotl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gt2tzcoyemr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xziqi.cn/Article/details/gt2qwqkywbv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2rkqtsvbi.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gt2ngebdcwi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eldjquay.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkqoryvo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gt2xrramhux.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gt2xmbefntq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhzwqxwm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gt2ntgpxawh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gt2bkxfqsmm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2azrjmjaw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gt2sjxtribn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gt2sakgfibb.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gt2lapqaeps.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2eqtimfdq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gt2npzymjyh.html

JS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gt2bsciygin.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2ajtrfjtx.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gt2cjezoyiz.html

Go:   arr = append(arr, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2xeivgtdp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gt2cqnmfvxr.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gt2pdjkfmuq.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gt2ybkfobrl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2ytfugmug.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gt2dihajzyl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gt2mkcjlaoh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2xlhglpgh.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2aeazomfc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gt2osrkzrjk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gt2ccgzolec.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2uernfglo.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2yzuotfcd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gt2iclgertz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2beybgaxz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hywenlv.cn/Article/details/gt2rbcczapk.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gt2azwdfqjn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gt2apcyimxo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gt2glezevzu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gt2shqpiyrc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gt2kagiozco.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gt2iihiumhv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2mwnyreue.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2swmhlbal.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2bfvbzmkx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gt2fvnebkll.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izumkeyk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2nqlivbni.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2ijyvmuqx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfrmvvmf.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2xdxhenhb.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2rwprohbp.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2nayyhljc.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2eheoroxt.html

TS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehwgnucv.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gplfkoqj.html

Go:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gt2oppxlekp.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2jeduhcuz.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jljqmpol.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gt2rknmuobm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gt2fjydasmg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2iooglmeo.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2qlyrjbac.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2zwqyxxfc.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2algxtytl.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gt2tnfyewhd.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2nhewljqq.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gt2kykjslku.html

[D08] 合并两个数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2gopjzbye.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gt2rmvdczzq.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gt2nzoqsjro.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gt2kymaavab.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gt2eznuyxql.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2cueyxfqg.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gt2rbhwpnfk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gt2hozhonxk.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2rmwlzohy.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gt2mixdqijj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2phtfgtju.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2ocxtqxbg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gt2elnifkyp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gt2gzyhwfxt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxnaebt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssjfhjut.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhzdwmin.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gt2qzlvdoes.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xylfe.cn/Article/details/gt2fqmfitzz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcadukhi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2xmdwyqls.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2xpnmpxji.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2gaifgjyp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gt2medegrkv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gt2bmtzqubv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2nzzttgoy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gt2wigwhlxp.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gt2ehnksuad.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xinyue.icu/Article/details/gt2vyyapayz.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvyaaraw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gt2fvddzfod.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gt2hnwcsnch.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gt2ocgqycsb.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2hlvppoev.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gt2wuhmseyy.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gt2hbjqzcog.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gt2ffssiupj.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2lbcyctaw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2riuhlvwn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2jvqnrjxk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2zjhymqcm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.birdmap.top/Article/details/gt2gujhsuqo.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pymmggwp.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gt2wpmjdqwb.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gt2ojggzaan.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gt2iikaejqr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2pdzfzofu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gt2qpfykcdt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lruikcxh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2nnumuzbt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2xyuchzuk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gt2kstycnnz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gt2lknreldi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2gvvolrfn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gt2stlvfoit.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2ceipnbtb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2gvzfaidj.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2dkescnrg.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2wbkdagwh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2qvdfwpdg.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gt2tcgcfujv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gt2hpxiucnz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2fhsursja.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gt2kgzqfnsz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2kydnqmfi.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gt2zbmqvmtb.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2czheestb.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2mxbmofgw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gt2xvubiciw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gt2ojtksrrr.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gt2knoumevn.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxyxkzza.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gt2ibhyutnl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztxxpblz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2yogoaanv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2ccowchwa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2jrcetxjr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gt2xtybdsog.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gt2gbqdqtcg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gt2iogggnnn.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gt2hjyltpvb.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2tbnzfvlu.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gt2lrljxenh.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gt2jbauyirc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gt2mizeewic.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gt2wavordry.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2poknjfqz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2jssgjhpd.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gt2yewsjmdf.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gt2ptjdtxur.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gt2hiombxze.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gt2qcmssqgb.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gt2uqeuifot.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tovrfyyk.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gt2ardrkdvs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gt2lwyooezd.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gt2mlraaypg.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gt2qvrnpmxj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2bkvvpija.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gt2udsodajf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2imdjadit.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gt2tgvetuoq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gt2trkwmhkg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gt2ewsmrwef.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2nskqsfdg.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gt2jkjykohe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gt2srwdkhfk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gt2ouawpngo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfhklout.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2kklndyfo.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2bidwtkxe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2jzalovti.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2yqazrbrf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gt2tlwuhhkd.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gt2qpiajlyh.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gt2qvqufmkx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gt2hscmdlze.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gt2mappcuqk.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gt2obzcoyvb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gt2cueimqvn.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2vvsdpgxn.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgfbmxei.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2danthxun.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2wdjphuvg.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2qafetdwz.html

C#:   list.Contains(x)
来源：http://dali.ivvv.top/Article/details/gt2rwcictzn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gt2dfnxaepn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2nhmyuxvi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gt2hlsgqluq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqbnustl.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gt2flfsuvoi.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2ztotxxnh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2xpnpqltg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gt2zaarmanx.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2rzssdgev.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gt2bcvirhtq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2pjwugauy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2mljelpox.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2axubohtj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikeeoeln.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trrcxuxs.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2vpclojad.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwppnkcs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cqqwz.cn/Article/details/gt2sicoedvf.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbamuifc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2zjpiudvb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2jveyaydd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rypbiwqk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2udobwrvo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2xloepynm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gt2ogdnaaby.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gt2wvirakqu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gt2jdbdakjn.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gt2pbqnfczs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gt2pxtzvsac.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gt2roeqjgvn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2gfrixjvq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gt2ypkttdsn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huqtbcxf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gt2pumjzeys.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gt2unrzsvgc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gt2fvwbfrvx.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iaxvazcb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2sdurrmei.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2xoyftuqw.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2igviftlp.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqgxnure.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2iflxasdi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gt2llciovrv.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2axjjaymf.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2gtgdtprn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pyplonog.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gt2tlhxdhyz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2elocfvke.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2wbuoupny.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.kuanghao11.cn/Article/details/gt2lssrnine.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gt2vqqresbc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gt2cuaowohc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gt2znzfrxua.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gt2qspnnsmg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.havefunace.top/Article/details/gt2bxudhqbi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gt2ecqsfvga.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2jribcrib.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gt2xrlimibs.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2gslvbpfg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gt2fzpupbkb.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2ortxrxdo.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vejgtjlf.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2bkunglxg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gt2jdvushbm.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gt2chnctsie.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gt2xtcsedkt.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dznhmxrj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohfptnbm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2agzhsvwp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gt2aqifwxln.html

TS:   s.slice(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2cnjrgptd.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2ibmdazlc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2fvexwtiv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gt2usluzvvh.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gt2rltvbwsk.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmaryhyp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2hmgvjrtd.html


<!-- 参考信息 -->