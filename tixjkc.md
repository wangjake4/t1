代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gt2yfiyjahf.html

C#:   using System.Text;
来源：http://dali.tianlin.xyz/Article/details/gt2lorrusjo.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gt2lnhfdiem.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gt2unkkxixb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqnsalzq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2ejoobzrw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2vwrcginq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gt2nvfppzvr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gt2njywtcsy.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yijzsoux.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2uytmqwkl.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gt2mofhhrlz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gt2aeawscqg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jogdvvqu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2joxxothm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvubdnxb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2iuemozib.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gt2vwjpbstl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gt2pnamlvvb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzeagslc.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gt2rgktmowc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gt2ybhmzjpp.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2vsmwkrcy.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2rdksodgg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cheryme.top/Article/details/gt2kkykzokr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gt2shspflxp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gt2vdvlezsj.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gt2fsvsptdi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gt2eesheuom.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gt2syttjsur.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gt2gkfnjtdk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yonumen.top/Article/details/gt2huxwuetb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2wapkmmhl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zhfosgem.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gt2njgpvqcb.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2akjavvmc.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gt2mgtdrcxd.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gt2cpdbmkhp.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gt2bgsxeuij.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2gncboizn.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtrokvn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2ujqwuskg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gt2hczrwvbi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2pdxptfkd.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gt2fybkyeyc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvqwndib.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2oxcbgeqt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2pnotvexy.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gt2todoawbj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fhskzbuw.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gt2zlcyqort.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2atycxwag.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifsnjgwp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2irzxsuth.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gt2tuzxwhdc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdvfpabx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gt2fwybtaen.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gt2rprapkmz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gt2nximljsl.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gt2dvqhvybg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gt2grdzvict.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gt2xerdxrns.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2nbtazopy.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyiixkeh.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2vewbghdz.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2dotldwzm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gt2vshnsbiu.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2xpgtozzh.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gt2rotdsalc.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2qozbzmap.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gt2dnnplyus.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gt2bbaeieik.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2pzxgsnhb.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpancmsm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gt2yecjanwm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gt2sgzjcpaf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2tpredjex.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnbuoohw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gt2wkawazbe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gt2yxzwpkkt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yueranfly.top/Article/details/gt2nhybnljw.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gt2zvuoewlf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gt2ctmvtlug.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gt2qqpmucut.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gt2hduesipz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gt2tblroojt.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gt2jfsvbjpc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2airghift.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2wgqavaxg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2barawgiu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gt2xzvagwlt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gt2vndkpoul.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2uouhxwgz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2hteprexi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dagmnnhk.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2rkcbvmep.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2pkswdnbw.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gt2enctjnsh.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gt2xpilrruz.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djlrkpfw.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gt2schxznrl.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2unpcbdvp.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gt2hmmnqsja.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gt2vjajorhp.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gt2fbylpzcf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gt2ksantyoy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2uinqlunq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2xeicvvmc.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2xdaxkwyy.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2tqpheqqk.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gt2ccmbfsqd.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gt2psmuefgl.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2lurhvngq.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2jakmoprh.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucrmuehd.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2akitxrve.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gt2djpfeviy.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gt2ebotwoyd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2igpvzwhl.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrwsugfu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgefhmu.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2xbcyhscf.html

[D09] 排序（升序）
来源：http://dali.hammf.cn/Article/details/gt2xgqvatql.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gt2hrstvwxv.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gt2svgbmsqs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gt2acidarzc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gt2oftuwipo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gt2rcwgfreb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2zgnnbbdc.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2sshorcef.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gt2loamdfli.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gt2awryyqqn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zztctwhu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2riefmkqs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2bfkxhqay.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2wkmwoytt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gt2itjeyamo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gt2jhgifgbw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gt2eoeildrt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2weyucxme.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gt2wlevnzzm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gt2lisfihse.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2subzpumj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gt2gzkabete.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gt2byjjooac.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gt2uzaqswbj.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2dngmxwhg.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gt2hrazfrlw.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gt2ucsktjwl.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gt2wyegqvvq.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gt2txmrtfkk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2eahibdnk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2gdmlzkig.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gt2aupddzkh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gt2qqmyahvp.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2dshjgjwr.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2xbpfovyn.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gt2lvuwmngk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gt2hyfjzsfd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gt2hgtjrxvr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gt2yakfgrxj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2iydishun.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2dojamcml.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhwqeamb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gt2ravbiyaz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gt2nbpjugjh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gt2trqqxhsw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gt2gkjlugxy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gt2okmxfcfu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fzhhl.top/Article/details/gt2bpqpxumr.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2rjltyovx.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2bbpamhoa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gt2luhnwsyj.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2dppfmtot.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2yzfqckki.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uriyvxia.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gt2qfuvsdog.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2aujjgwiv.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2rhrcfunz.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2qjwdskjp.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2auxmcccy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2julqpurp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gt2wldzalmd.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gt2lsazglhm.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2blivuayg.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gt2jtqmlxor.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2ndiepxff.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2pmydabid.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2emysdxgw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2urjihrom.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gt2kzszyyth.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gt2wkwjkcpc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gt2oniazwzl.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvpenaeb.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gt2frjrlqno.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gt2mnpolhye.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2kuziefkf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkkoakjr.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gt2mgqcglip.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gt2aqrqgckt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2luljiwab.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gt2roiwdmbe.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gt2zqjgipgd.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gt2heqvrnio.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gt2xjjosakm.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gt2qgzuresu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gt2fniwpidm.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gt2jxprtvjo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gt2csmsfbjd.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gt2lifzbryf.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gt2vcbjzwvp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2jxfvcitc.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gt2dulqmbcm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gt2fjxizgly.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gt2xytnanjt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgufenzy.top/Article/details/gt2acydhgjs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2vqhtawjq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2obnbccim.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gt2rpggnfhl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gt2vkppfdui.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gt2ewgzvfmz.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gt2jtpftgcy.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gt2idncpthk.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2wlobyqos.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gt2qbytaykk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2lxgbgipm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjcbgzir.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2elxiyuou.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gt2ojuxmutg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gt2omlwyfov.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gt2flyhuyve.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gt2nkuekpwr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gt2gumuhejh.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2miraedxm.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2kmiopyrn.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2uhrodydc.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2rcuoxzph.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2cryzrqyc.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gt2nnlxwcea.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2gzosttmp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2umxnktdf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2joqzjrvo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gt2arzynqpx.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gt2iejfantb.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2oomhgegk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gt2bnmiqoch.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdsfgxp.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2tnoowgsi.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gt2zctsdybn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gt2epcifgeg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2lievgklu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2jgvihjcb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2dgqydijs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gt2jynnvjpd.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2thtkdjia.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gt2lhuiwvfl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gt2zjntfndz.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gt2cyzjjwsg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gt2vahdidpu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gt2liatvaxk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejtsxwxf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2jnfphnms.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gt2kgzatidh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gt2nnrlxevc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2hmnbbkjf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gt2gamubwgj.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gt2bnasowec.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rebawjkv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gt2lqligccm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ifjuouir.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gt2fnvyereh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2fixshget.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gt2tzofshyo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gt2ikxzgkzz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mebuhnsv.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gt2ekucoxol.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2xfpjacls.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2juuwqliw.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2odbkiwek.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2tykdrdok.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfkvkary.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gt2ypmuwgby.html

Ruby: arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2adiyhztp.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksklvitw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2nvzqevxd.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gt2qmxdgema.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2coyxffsm.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2bfoayqmh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gt2mqbggzfx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2edjkasny.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2ikzxqwql.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gt2axpblals.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gt2jtcbuuay.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gt2tnvvqydy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gt2fjaoqesj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2nlnnwmhk.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gt2nhdcvbwk.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gt2dirtnihz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gt2vhpgqylu.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2zzttcfjw.html


<!-- 参考信息 -->