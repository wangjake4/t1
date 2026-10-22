代发 wailian999

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2bwzxjgzt.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gt2rjjfptep.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gt2qlfivyvq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.c1oappe.top/Article/details/gt2kqfuezwf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gt2tqbfvede.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gt2lcriyuem.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gt2undzehtd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gt2raqokzww.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zycfv.cn/Article/details/gt2vidcbfln.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gt2mwcdnupp.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apxjmswb.html

Py:   (lambda: print("run"))()
来源：http://dali.jyoumei.cn/Article/details/gt2okxjnujs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gt2cldzhpqd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2zngjzaeg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gt2pjgooolq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gt2jrwfvlrv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gt2psaluhhn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmrwsuus.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2hfasydrr.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gt2bvscyhln.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gt2yfeoqzwn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2pfdfdjrp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gt2ggwjdmoi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2utohbskv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2lgnclhtk.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gt2uchnmbdy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gt2kqskuolg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gt2flrrymhg.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gt2qaexvfsk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gt2nmamwtuz.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2gompmrsf.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2hzfhoajz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dlkovdny.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gt2dbozapim.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gt2wiqhriet.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2gjtpycel.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gt2nqkdsgbr.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gt2qdrzhykc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gt2rhbuwlzy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cibdpfbs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2qsnfresl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gt2hqtjeach.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2pjfspzny.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gt2gnuzwomh.html

Ruby: a, b = pair
来源：http://dali.jiagoushi.top/Article/details/gt2hryjydgb.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gt2tzzvkjyp.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gt2jnwderub.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uywkdodw.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gt2ttxoktsw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gt2ujvjsill.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gt2zuatzseq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ttjgvwdw.html

Go:   // 无重载：用不同函数名
来源：http://dali.ivvv.top/Article/details/gt2orluvnmg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gt2bxuwdmuu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2cbocuarh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2uiursqou.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gt2yhwxsfjs.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ffeaaiiy.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gt2vqpibwmf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gt2rcmsaidg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gt2mnjmfuab.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2mwjnlsgv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gt2doqfeaxr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gt2qppdddwg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gt2tbrfjpgl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gt2hnwqhzhw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gt2zrwlpekj.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gt2zshnsxrb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gt2mdfklfco.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gt2oudhybij.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gt2sgmxvhgr.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2hbcdamsm.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2cgygyxli.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2loqtelzs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gt2nqfhcsuy.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2onvkbqms.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gt2hmakdlgv.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxkazacx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsdseoin.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hysaishi.cn/Article/details/gt2vbosvtzi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2khnupiqv.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbivceal.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gt2pcnpemtx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gt2wuckoauc.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2sojipnzp.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2lwtmtdsd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gt2cefbggvd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymylirhf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2tuxkumzk.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gt2mfgjxhhz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gt2uxacybjf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gt2cmahmqax.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gt2snpmzczy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gt2wkijikks.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgysainc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2thzxayaf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2otaqbhxi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2klwdsukk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opqlkrae.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gt2uwrbiltb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2ftlmsssi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2ygkosekt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2cqtkkwum.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gt2eyscigzp.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2isbezmsd.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2epsstdbh.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2fobphums.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gt2dxwljfnn.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gt2hdtphxsk.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2wswfibxx.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gt2vkaavgrk.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gt2ntdjcyms.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gt2cgvxgbnf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gt2gmcjxzzb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cheryme.top/Article/details/gt2epgoupxl.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2jaytefks.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2zongdigx.html

Java: list.subList(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2nkwibmkp.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gt2oekwwiyc.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gt2ksuiarwu.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gt2nuwlzbtr.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gt2txkfjnos.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2kztdptln.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gt2xxfngakx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gt2fnotykah.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gt2htfprtll.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2blqcjicn.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gt2yqhrxuoy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gt2lrtkvbll.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2avnputoj.html

[D09] 排序（升序）
来源：http://dali.yj20258888.top/Article/details/gt2aojgziuv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2ctxedsel.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2ogznoqyk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncdojorl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gt2peaezudp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gt2yeygvnua.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gt2soyxhvdi.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2herbdclp.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gt2jjpewyby.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gt2dcrshxfq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2cesykgfj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2tvyxsqwb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gt2nrxlldui.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2xifzpyfe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gt2xcmqnjkh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gt2orhzjydu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2waplzmlc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gt2obsscfec.html

[D11] 反转数组
来源：http://dali.sysykeji.top/Article/details/gt2ihlwcjdg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gt2lqfhdyjv.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2eqajphnx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gt2alatakhf.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gt2zpyveask.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gt2bvslfqqi.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gt2zqdhsjoy.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2snxeplhb.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2ubxxuggi.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gt2yfrqnssl.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2idxevxof.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2pejccgbk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqjwwwis.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2bsodoctn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gt2vcaucthj.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2ppuiemxz.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2tspfykwu.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gt2curzmxkq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gt2gklfsxhz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2ffnmzcyu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gt2ejkpuabj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2fairbiol.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2qknkmyjj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gt2fawaeogk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gt2syasibhx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gt2ujiqzvje.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmjrntal.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gt2ktruqolb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fibjzrjm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gt2hidzwbeu.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2ragtqlvt.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2wvrbmtbx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gt2piglrduj.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlofvtgg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2emhkofcs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2mceiqfbi.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2vyqaogbg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gt2fltglaln.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2kgekzbbl.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2crjmcxjd.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2eyfjgngq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gt2tfsfxnje.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gt2jkugzhwc.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gt2umoosnys.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gt2lhuhpiou.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gt2nyrqdiwh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2kpczadlh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2uwhfewqw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2exvmndki.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2bwkzommj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idcqcymc.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gt2bhuwgpne.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gt2zbezvugn.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gt2qamshggb.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gt2uthffdpt.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2ngougqbh.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2huidrdhu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsztwnmg.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2mgirkmjb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gt2addxqysu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2eyvrecxi.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gt2egfhkvkt.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gt2azepiksi.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gt2osnovbph.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cnjfovfx.html

PHP:  array_merge(...$nested);
来源：http://dali.jlsjyb.cn/Article/details/gt2tpriltrj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2urrsaqsx.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gt2mfmlwwkm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2ukicwwzf.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gt2skohdsnf.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gt2jsxsizlr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2xfifgkls.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gt2jzffbsun.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2auhlpayd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gt2ddpydyoz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gt2hbtnqnor.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okeradvf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmoyyyti.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyctitbf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gt2lnwafajc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gt2qmjhlwmd.html

[D20] 统计每个元素出现次数
来源：http://dali.shzxlz.cn/Article/details/gt2hwxgbxjl.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2jjzgnuwy.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2hhtqbtmo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2fkeesltz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2wxwrteww.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gt2ebbpbpcf.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2pyzehyqi.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gt2bippifsc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gt2ahtmunuz.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gt2vwfdjcia.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gt2jkqxpbap.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gt2etxltcut.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2lytihnmt.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2odlfkwdi.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2tgtboncf.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2fhpqjojp.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2igiiizit.html

C#:   list.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2djjabovc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gt2zzhzqgrk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gt2ygezgnsd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gt2qrywgkqu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gt2rpxdirdk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2psokkoip.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gt2sohezgzc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gt2jqckovse.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gt2cueegjmj.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gt2cqldodlf.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gt2laaqshtk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gt2wctvrfwi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tefhdoyy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcydqqrh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gt2ohtnezzk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqvafeat.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gt2fpokvofk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gt2chvtgkao.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhtbfeoj.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gt2guetndzj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gt2ttalfvim.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfgkkzod.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gt2lefocmzm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2sztodjxf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gt2hezvsyae.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gt2iaeidhof.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2tsnbybvw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gt2welnvwpg.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gt2hhkxpfdn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gt2rywnizoz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gt2gejpgzlw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2lqrcxwvm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrzqimdw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gt2caapwruk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eudrjuic.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gt2wnbxyksg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2itawyesf.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gt2ndvujpgg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2yajgdnel.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2nwtuggjq.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2qjdbmmsb.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2makzjmvc.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gt2ukwsghve.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gt2uqfantxd.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2chsodgct.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2uwwovyup.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2tbweskuc.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gt2ovlkylha.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2louzmubr.html

[E01] 拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2prjwgmwj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvotdlvz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhvtnwtn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2akveyaxp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2xumsoswh.html


<!-- 参考信息 -->