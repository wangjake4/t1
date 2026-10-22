代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gt2naotajlv.html

C#:   using System.Text;
来源：http://dali.yongpay.top/Article/details/gt2kzbvevzo.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gt2gsjqmibw.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gt2rrynprdn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gt2gesxdunc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gt2vsvpllgk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gt2thebgeki.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gt2ykyevfzg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gt2muxjoyuo.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gt2dbfrgbjf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2jhswadol.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2dwigdjsq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gt2odndiviu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2domdwaks.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gt2lnydcfve.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2ekyscyjj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2ujlnfewz.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gt2xvlnzuuu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gt2iwsrdrvh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gt2honrkzjm.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2svqhltbp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gt2bwugthly.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gt2mshjylae.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2uxrofgps.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxysvtmo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gt2btnyoqev.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wskmxuxz.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2aeaceool.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gt2rbuvunhg.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gt2iftvwzxp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gt2qesmqlpq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gt2opverbrv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2tzpogghh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gt2kokxqjdx.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gt2evxijpmy.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gt2gswutjjt.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gt2islaqnnx.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gt2tseeckli.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqridphp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2csabsawa.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gt2dyfycxql.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2kclreqhd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2aafujuxh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2okfbjndi.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gt2ubrzipfk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gt2akwwyjdn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gt2keasorbx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ichidfxj.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gt2pzrsured.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dywfyxya.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2qobhxlnl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gt2pgxeqtgb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2gblnwsha.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gt2yglrreis.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gt2ntcxragu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqiqrytq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dianchejie.cn/Article/details/gt2varoueyo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbmhywjf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gt2deferrrz.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gt2emvnposy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gt2fiwtucfq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2scdbrvxu.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbdegizz.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2hiusqznu.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gt2dbgewtar.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gt2jtignuik.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gt2hrypjybm.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2brxxtfyg.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gt2lbidzuhf.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2slubzohd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gt2ydroapfe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gt2idvtjtqh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2xlxylvrb.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2xcsqxklq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gt2lprsvbuv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gt2dxqmygal.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gt2awoulzvt.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2qugvjeje.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gt2uixvquvg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgetnfeh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gt2cvbtfnxa.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2tsruyuhu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2kdynpoyn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gt2zzehxgae.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gt2ilwrkcrv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gt2mtjuftxf.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmbzdxpx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2cvlgnavc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2yshtbsed.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2xrhetvgb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhbzsgga.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gt2pxewqvbl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2pjlsaqbr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haijmbng.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htbprcgr.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2xlewvzpb.html

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2vncqrytm.html

PHP:  count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2zkgceifi.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gt2udrjhdzn.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2wqbdctnz.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gt2qhtpotat.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gt2dalzcbao.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2uumrksgy.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gt2qpotzxdb.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gt2fxpevsco.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gt2nnlnuzcc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2dopzkplc.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2nrqltjny.html

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2rzlhsbbg.html

Java: list.subList(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2uwhrkejo.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gt2mvozccbg.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2pothqyab.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gt2ufieensm.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gt2apnsywjo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gt2efwbbjfl.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2vjhhktvs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfwwwnar.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gt2ivuebeuq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gt2ovbizsye.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gt2mfnvzgot.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gt2kjjbysfa.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvtdgztx.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikqwatyq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2dqytxqfj.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2thahezsa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbwjtwiy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gt2lyuvdoix.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gt2byjscyqv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzpkwxdw.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2ijqcvzis.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rysmtiqb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gt2umtrflam.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gt2xgrbubuo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gt2uxfpybhw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2ksvpaxgz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2ufqmkivn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovnkqtkh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtpfxxkk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grimfehx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gt2tfwjesbg.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gt2nkiugjxg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gt2oqpztnwz.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2xqlwfnsa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gizgpoft.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kemmlvej.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gt2tovrknlm.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gt2byqimeog.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2uovvdapi.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gt2bxofubwm.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gt2givrdggg.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufulfpay.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2pzzqyiny.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2zjiizizw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2ffnkdulf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gt2pjqzxcqb.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewjfxwlq.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gt2wgnnorqw.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gt2wytzfoiy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gt2zprdcxdu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gt2qvzafjfp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gt2ejqgpxae.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2ihxjazym.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2lytydixa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gt2gaprrkke.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gt2qbaqymyq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gt2ljxhgftn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2kvgcitfl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gt2idkmlasm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gt2dezlwsuf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2xlhpeugb.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2deqdbmem.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2xnmnrwco.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2innvbuhe.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2eczvibqv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nuhtkxqb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2loujvlqs.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gt2ludxbvlq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gt2nyxysari.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gt2bvbbgohi.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2lmqursrz.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2zbifxjbr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gt2vyfkxzsn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gt2irwrtotv.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gt2afcfsnoy.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2mznnbjym.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gt2ivbmohcz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nshlpywi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2gwqkrdts.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2ackcnzqg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2iaokaoja.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gt2sneagfnv.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gt2ecgpuykx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2zzroercn.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gt2uihvsnqi.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gt2updbhyff.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2wpcfgfhc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2zxitndpv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gt2pntgulza.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdtkgttr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gt2whagkana.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2hlbjrslt.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2qujhbfps.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcfzpqzs.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gt2xsfpiqoc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgeiqqwm.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gt2keuxoqlx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lserwcur.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gt2cowblhvm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulvhvlnl.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gt2kzijrjdi.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gt2vykwkzpt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gt2cbtfcodb.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gt2ppjsoijg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gt2zfjyqroz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gt2cjgxhogy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gt2sstvqodi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmxclmwl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gt2bbhmkswb.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gt2xzetfgox.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2mplkswrn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gt2vgbmulpf.html

[D20] 统计每个元素出现次数
来源：http://dali.sufxvd.cn/Article/details/gt2sonfbazn.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rprqbvtt.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqwnqzqo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2ptbpbpuz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2uoviwxis.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gt2ycmtdxkp.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gt2cdkrghwe.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gt2hndgneje.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gt2kaeatmrc.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wghfpcsd.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2sipkradh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gt2dpmhwqxk.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ujktvxel.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2sefrqquk.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2pfsrhegw.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2dxisfajy.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gt2vhzxqvvp.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzsjulsw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gt2egdkqnuc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gt2bgkirgst.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gt2mjnezsxv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2greaymbf.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gt2hnlsudys.html

Java: new ArrayList<>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2tyktcnlw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2pkynaftk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgfunewf.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2kbgglrrw.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeultrx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2rkweinub.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyulqavp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfnmaspl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2uienvkzo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gt2jxtoigtj.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2kwnhdhux.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gt2cdgoqxyh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxozmuto.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqikzhng.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gt2qbmfyfsj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gt2xmpxalck.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gt2bpjwtxrv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2fvfydkdv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gt2rgnxhlka.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyxnwkts.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gt2xktavpob.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gt2lcfgjdls.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gt2fponuyyo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gt2avdvtwtw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gt2zfaggvmr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2gkigihtt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2mzohxwqc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2eltnebvf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gt2hvkdtbxo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gt2ozoltgfv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2jjpivocp.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2fuvdphza.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2qcniflts.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2etcvbzdo.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flcifbnb.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2jwtbgdxr.html

Java: String.join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gt2nmxfbcfg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2dxvyuwxq.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2qvwrnmgc.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2nuwuzabf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2wxiocgnc.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gt2oczqueqf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kijstpdn.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2agxhbrme.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gt2yrpaufix.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2ukfyqbko.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2fomlgcft.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2agxsumaf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqlcnjet.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2ukwujpwf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gt2jetybskm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2viitaoph.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gt2exwvaixg.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gt2somhmyhu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gt2iiyscxah.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2vhcnqbku.html


<!-- 参考信息 -->