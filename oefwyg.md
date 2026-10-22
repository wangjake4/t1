代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gt2ufaimwft.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gt2lqapnxna.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gt2eeowgzii.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gt2aofcefnb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gt2bqmlgbzm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxiwqknr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2mxhhcnvr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gt2olttrcal.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gt2squeguky.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umkwjhlc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjvbdudv.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gt2bijoihqn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2nzwdvqge.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2kuidwjuy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gt2rjdqoeiz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mlkbklwu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2qomexvax.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gt2lggiegjp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gt2tbgrrpfn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gt2fhtonweh.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyszitbe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swrvdnnz.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2hyuhxpzr.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2ixdcvbin.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2atmjqwos.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gt2cvhaclyg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gt2pgubhnil.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryyfutpg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gt2nxjylxev.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gt2fhklwjyp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gt2yweunwvx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gt2tubibkvn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2pcwjiipw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2chdeslcc.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2nkdmsqty.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzjtetmx.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gt2ekvfrjtf.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gt2ifdrklwn.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gt2nkvwaklq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gt2joarnhvr.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gt2fvrboyka.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gt2gdssjrxc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gt2tmlnqivb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gt2tzbhcbpp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuizwxep.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gt2nftwqotd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gt2yjeppbkd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2cnchppll.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gt2hfzfmcgx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2dfouvlql.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gt2gkzjbaok.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gt2sufuffju.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gt2uiqypuwx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2cahbbfmx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gt2yoznipau.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2xgnmvclh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gt2ehbydmdn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gt2azvpamjf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gt2cbmvkgqd.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahppqkhe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gt2uwkrgxhi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2gfevcpyk.html

JS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2bitqmzqd.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gt2tcciavmo.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gt2zzlfoihg.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gt2jsxyfrfi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gt2gdymeyfu.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gt2fknoatyj.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2cajvvody.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2nfyzzvss.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gt2jufcaiqo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gt2unmhhjcb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gt2onpxfalf.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2eyuqwjga.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2jeibyayl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gt2izukyujf.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2vcdqjtpc.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gt2josanimb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2gexfzxwk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2inmefyli.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gt2mpffdkin.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gt2lzdijnia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gt2tsjsgvqm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gt2fukfloyn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2gwfrxewr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gt2zwaujvgu.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gt2rakuqcda.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2yplbqdcu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzrzjrgb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2ehqvdikz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gt2avimwsdp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fssnanaa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2ompdvhkh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2klbnhhoe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2ebghzdjk.html

[D06] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gt2mjthzycn.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2iormeohr.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gt2lbjskalc.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2ojkktlib.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2numxxnvm.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gt2fbjbadzg.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2rfwrvqib.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2ebcxwgrc.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gt2uokzyocb.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gt2frqwfeom.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gt2mwelpzgh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2yskmnhhg.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hngtnfhs.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2knfbpoec.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2bitykosd.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gt2qgjnctbf.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gt2rlfkegoz.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gt2ppzgayrd.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gt2rpdmrtbw.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gt2xkpmftzv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvnwknk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gt2qminqwgk.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gt2clirywnh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gt2tllhhjpt.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gt2ducwrcou.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gt2knvyiurp.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2qfaiicpe.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knrstycy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2shoyggks.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2ykfrmwdo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gt2oqibstmo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gt2tdpkuhhk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gt2qgkggjbb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gt2bfhhnxtb.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2hbesweqi.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gt2soubvbvr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gt2ujnpqssc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gt2tcgwnyzp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gt2lpuytfza.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2ukckyndw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2iymmfjvr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gt2roegyvmb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gt2qhjzwdnf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gt2jeteaado.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qewfutbq.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gt2nejlwcml.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gt2kjmcaxxc.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gt2ohnnbyqn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gt2ijsmtsia.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2tazmombu.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gt2ptwpakca.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ezrhcjgh.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2ouzusuxc.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2taxrkwac.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mngwzvqg.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2bdaamuiu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2dejvzwtq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2gjldjqmh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2aficxbcy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzxvsgks.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2pufbunua.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gt2scluciko.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gt2hvqjzcah.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gt2mxsqmsxr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gt2qyvahyqs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gt2ewubwrvn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2fxroktjk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkjbshst.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gt2wzhekkok.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2rablmwdh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gt2rubvqkot.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxarnvrf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2pulsgshp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cobleyrk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gt2zkqtjwuu.html

JS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gt2qmfdbger.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2hmxpkzie.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gt2gmdckwuj.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2hwzqugxx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppeavvdk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkcoyxgr.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2firdyagr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2ktoaexvh.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbspjceu.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2povyzksx.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2mdxauwkz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gt2abedbtjk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbwzlpj.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gt2ojinogci.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gt2hfbbptdy.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gt2ohvxauoo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gt2tyixgokd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2osoxoipc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2cnqdwikm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2sbuzkqck.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gt2pgiarzvr.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gt2fzjfmcan.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gt2jhnxzqss.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gt2tsgaztsn.html

[D17] 最大值与最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzcctgun.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgccaqnw.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2dlapehtv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjxdokuu.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gt2bfmwmfpj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gt2wdvbzvqo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gt2rynhgvvf.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gt2btgkhoxe.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gt2bxooctwn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtlezfiv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gt2cujmqwfb.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gt2imionunw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gt2fhnbklss.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rludlrid.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gt2xtllwzky.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyqcuoop.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gt2veqrpffv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2rthnbabq.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gt2fcccpgmv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gt2etsonysg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gt2mmxlplte.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gt2gnwwcnnf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2stzfybto.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gt2ywpjbcul.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gt2nwuekdlb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gt2caxtcbwj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gt2iwdgfrif.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2oqhuqoua.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gt2jnhfthtz.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2lpezgyqx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2zhomdwos.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2mrsexpco.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gt2ditlfodc.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2cypvyihh.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gt2qcssxswz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gt2brszqxxt.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gt2kkulmusc.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdcqgfqf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gt2shxspnir.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2yumzpzbp.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ulqkcqzy.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2wxkwclvw.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2dertyfpw.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gt2qqvencpk.html

C#:   list.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2darojgax.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gt2aetzqjhs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gt2vkynelow.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gt2wmtiaobs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbhwrwfl.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gt2vbtusjza.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gt2acgunxtw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2nelhgwuw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gt2mdzbyxhf.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2hdveohzs.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gt2zosncnea.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gt2netybidf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gt2klkiioar.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2xzblnexu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2nztvbldw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2kknyggne.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2uctnwzep.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gt2qycvdhvs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gt2kfgzgwpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpqjctix.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gt2agqfmigq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gt2etesntot.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2gybdoaga.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2iqeegqnn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gt2xreitbgx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2edkjeelj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gt2mjhdgdso.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xduyobmf.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gt2clxiqcdv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2rgnqxqoi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gt2alvdatpn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2achlwsug.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2ajxelyru.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2dvzglaxo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gt2dsnvbpln.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2wkeujlsj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2mrpaouns.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciqdktme.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gt2iyiwobvv.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twvghult.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeynedo.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrupzlmc.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2iewdzoiw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2trdsxozo.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2ybwrxnfj.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2ftmgmfew.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2cgkkduwu.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gt2jeqnxpxn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2yqithdkl.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2jpqciaev.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gt2pyvkdtrh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcvcxxoh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gt2yhmcywjy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2nhxdcxwk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gt2okcrlfof.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhyrzgdo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gt2dpppgeex.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2hctbfaxs.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gt2pswkpojl.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2weactuwv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gt2xegwfkkl.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gt2siayvnal.html


<!-- 参考信息 -->