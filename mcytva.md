代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gt2mfrooyuv.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gt2hdcczznw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gt2zljcuwdl.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gt2pzbtpzyo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gt2ebxortka.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2zmgjobri.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gt2wxzriozi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gt2svzoidtx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdrvdcyh.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmqurvos.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gt2cvrpxbsm.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gt2mmvzofez.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gt2xahiohst.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrtwjszb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gt2aiyqaodm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpopspms.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tzmdwxbo.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynlinpve.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gt2nysukxei.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gt2amknofmh.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gt2hajthapa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gt2mhfgaksm.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2cvrfnebn.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2nubtvhjt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2gubumwrk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gt2adkfsasg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gt2eatxicid.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2riszhpxi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gt2rsyugzlo.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gt2qvrjvadx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.vqdsnc.cn/Article/details/gt2unovkhtn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gt2kwabrgxq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2smgwmyfr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gt2pktjnkxo.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2nirxrnpb.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gt2belwhcjc.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gt2tzsiixvc.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gt2pffjdtav.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gt2uifmoigc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gt2jezkiofe.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gt2xfnpqqkp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2pirlwydl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guannengcc.top/Article/details/gt2rxhuekgr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2etozatmx.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gt2cgegckcb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xinyue.icu/Article/details/gt2bnocafeo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gt2kotcvcyl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hxdhpypq.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gt2vfmsyzyn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ffswuicg.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2uhtaequh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gt2oiunxhuf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gt2pkiizhvk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gt2fupcwger.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sixbsqhi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gt2tknofgak.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gt2fillyxhn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gt2voozpsht.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gt2smrzbyci.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gt2jttgrmcn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gt2yvwdbkog.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gt2jcmgtcyh.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2eysiwujm.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2mnkekmzx.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gt2kpheqsty.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2rdajqyoq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gt2uxhsikyl.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvcomcah.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gt2xeeeycez.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2khtolthh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gt2tsoarmhu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gt2szwkxlva.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2jjleczph.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2swwieqmx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2qahnyzkd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gt2izgwagsb.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2vxpsdxfh.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gt2bywjzysw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gt2xujlscgw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gt2ujzbyicp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gt2zaxdiezn.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gt2axxkohww.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2yhhaxeed.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gt2whjpurtp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gt2xpcgaqkp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gt2cjklscca.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxtwcpaz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2vfmekrso.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2xoewuxea.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2xrollkly.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2zhghrdqi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2zlldshnj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2owfgmjqb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2imzjpuau.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2iihmcnlq.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bniscuum.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jggsxtwk.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2wojdunay.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2sjnnzkww.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2hdfayvpv.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gt2zwovqpgi.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gt2pvkrayoi.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gt2upocsolx.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gt2ljejuzrm.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gt2vcwyecol.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gt2vtkejylu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cheryme.top/Article/details/gt2wrjozdik.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2ilaawuwf.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2bpvncscp.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2eeunzoal.html

Go:   arr[1:4]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvvcxqgm.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gt2udlevftv.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyxikllx.html

[D08] 合并两个数组
来源：http://dali.smart0.xyz/Article/details/gt2qhskiort.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gt2rdpjzlzx.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gt2jnnmkbce.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gt2gfryrqqv.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gt2juplhdff.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2qzdlblpk.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gt2wnlfxmaw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gt2gdmpcnyy.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gt2njkpfwho.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gt2jhhwnusr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2lfcltykk.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ffzswusd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gt2whfsxudw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gt2diqkzeif.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gt2wmwvzolo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2dgeebocx.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gt2phyzeasb.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjbgyulc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glrbysbq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gt2ftlzegtd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gt2vormnfsx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2nowlhsbf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gt2eakmmpzp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gt2nqbhvnmz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gt2nakvhazs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2fwkudlfv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gt2gxhzglea.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gt2gpelmljj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgigfnxo.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzadroqo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gt2qgvjoddu.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gt2vcfsbxjh.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gt2qhuefrqd.html

Go:   slices.Reverse(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxlkcyca.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2ycyrqbay.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2nglrexxd.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axzwrpum.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gt2lrktbaoc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2iowbxmvr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cupqoayt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2wxwydowm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gt2uvxreivw.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2qgrxvimo.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gt2qsvsqtfw.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gt2imrrdorp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2rwcmblym.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2qubvfnsr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gt2fxgbhday.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2vqflraah.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2axjlhapu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gt2jubvimhg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gt2vxuoqcxv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gt2inodgois.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2jnvullyv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gt2ydbqeelo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2hvsmunfh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wloployp.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2sobgsnua.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2zelamgyf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gt2sztpuhan.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gt2pbxmowsr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2vsvgofbf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2jdthexuj.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2hghambdh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2hfyaxjyi.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gt2nexhwatu.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2syukvqox.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2bbcnuhoi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2rbiqnchw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gt2vsebktja.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gt2saskwpry.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gt2vaevcbbd.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gt2ukszebus.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2tuaqgpvt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fzhhl.top/Article/details/gt2marbxrug.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2guldvyue.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2uftfsvgx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gt2mgcvuwtw.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gt2gdwmagte.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gt2clawnbju.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gt2etburoys.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gt2sbmzzela.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2eykfqewt.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gt2rxyizcqh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jiagoushi.top/Article/details/gt2xhnkhdwj.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gt2hehwnqlg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2xacxbqne.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2nnaqzioj.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gt2zzajsgyr.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2xdevnqop.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gt2hgqpwglw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gt2vayysbuk.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fajjspcy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2yiuikfmg.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gt2tcboxkhq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2vyrmcnrs.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2ftlulqnb.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2dtbhifqj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2lziaqcxk.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gt2dgxfxtii.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gt2cltinfvq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gt2qysmokhm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gt2fkrittsl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gt2bgxjrxtj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2npcxwbrn.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gt2pezqsjce.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gt2aavlzduy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gt2ipdgtuym.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gt2sparjmmq.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2juzoxlit.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gt2qpoehcdg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2vgakonfb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gt2oajihrnv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gt2xljwvweb.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gt2qnwyzvcw.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gt2qmtkaqwo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gt2ficiephg.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gt2oyjixqdd.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gt2xijvpivo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gt2nwfibqof.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2eljoixae.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2lgkioenu.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2cegoupuh.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2yzawzlpn.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2npscaqyd.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ialisriu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gt2yodmhnbb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2hvbiwlss.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gt2pzgjxzlo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2qmhdwbnc.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gt2cnuxpowi.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylaldxcq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlnepivs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2pggngkbw.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2jjpkfudi.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luliuxmj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2gbfeicql.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gt2bktqsxww.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2pzcthnmi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcomydym.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gt2zzrgslcd.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gt2dowbdnsm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gt2zgoahkfq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gt2wctahkcv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gt2cyacxbdr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gt2fcrgclyk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2keacczav.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gt2gmgobwmo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtaylxcx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gt2ukvexwqe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gt2ucvdijsl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gt2unwphvvi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gt2eejetjmm.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gt2zhlbznig.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gt2vnbcvwif.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gt2bytmhcnb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwhqabhr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gt2wdoityys.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbefbvp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwjmnnyg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gt2abxjogye.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wathuoea.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gt2gahnqzcm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2hgyllaro.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gt2euxezqia.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2ddxpixlq.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2safgdzcz.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2zzpxrofn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2xrjgrjet.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2ytdytsxm.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2llevrglh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xxcbwiao.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxqqroqm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2uikcabib.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2evawryzm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gt2fzfmxhzm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2tfwvntja.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2mxlvzqby.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gt2umrxradx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gt2cpwqubzq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsdwskmz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2bgnfmewm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2tjnqldzr.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gt2oovwrxwa.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2agiitezx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pikydlfu.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2maukkhip.html


<!-- 参考信息 -->