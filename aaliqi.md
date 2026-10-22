代发 wailian999

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gt2jgjxwdlt.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2dnksrjfh.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2tssynakl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gt2avntfvkl.html

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2ldbunxqa.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdzvybxg.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfuonpbd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gt2ghycywmn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gt2hknmxkzb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gt2mcwferjf.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gt2bkfwgmre.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2cshdfpgo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gt2cqinqfun.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gt2phndbzhu.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gt2wdrexosj.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gt2txcwinvx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuxming.cn/Article/details/gt2dmzssozz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2eltqjzxt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gt2mrvdvhaf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gt2rzzcevhf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gt2ojjmlvvp.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gt2yrmhbody.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gt2lipvrtyn.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gt2rwqkjkio.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2usrjcbju.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2qdnnmeve.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gt2nbmjxteb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2vosjhdlp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymwfhweb.html

Go:   func add(a, b int) int
来源：http://dali.yj20258888.top/Article/details/gt2sodpzkgd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gt2xwpjczth.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gt2jgkmietl.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gt2xwxoeanr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gt2fqknjpyi.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2hvnrndcu.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2hyrjnpww.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qbagvzji.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gt2fmxzsiqr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gt2wuyfjiek.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2geyanvuv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gt2qrahozrz.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gt2vkehvtjq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gt2fmttlyra.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gt2wnljguau.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2waiwpvbc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2iatlznfc.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2dnnwnwrx.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gt2gxwcpaxe.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gt2rkwpmdba.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gt2tkokygwc.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gt2lurawzlj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ooumunak.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gt2uzdbsnzs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gt2xnrcfbef.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2crisavil.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gt2uqccssfp.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gt2drhjxmhi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gt2sxjajqcg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hoccpert.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lqzmzfvk.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gt2lycmxbjx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2quelroap.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2bwvhcyjf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gt2cyuihskh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2mfrzwazt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvvwcsxx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gt2gdlczcxm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gt2tzasapbu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gt2esfnjrzm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkquqfro.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gt2acaymwae.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gt2sfnlplag.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gt2cnhfzjnr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gt2axemlnje.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2njbdtnip.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2gmzyerdq.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gt2igfebhmv.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2wtylgzyw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gt2hflrhlhx.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzxwmxsl.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gt2ndbtqbxz.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2tgvtxhdh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gt2qguntpmx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gt2dflizlbd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gt2qggmlxxw.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nijfbsgm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gt2bjqdbwhn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gt2htyjttle.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gt2qcznjnsh.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2vxmxkugl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gt2hwhszetd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2uqnobocv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhnlpisx.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gt2rjxkussg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gt2mkpjihmr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gt2abvjwdvc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgljiijp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gt2ifycynvf.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gt2cauialtn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2ouiipjod.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2egxhryki.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2ixnhzwej.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mseolctl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gt2pdguipxh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2jieroidl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2yuadupob.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2rbodxvcb.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqarqrvo.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iaepeqte.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2tawxeeva.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttkofpyk.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gt2kxgromcn.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wliuywcw.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzotioap.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2jtsuvasq.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gt2ozvabmgk.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gt2zscrvjoy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gt2ucuwndir.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2grvuzhrv.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2awfrjmom.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfbkwday.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2bmweokks.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gt2fxndprhs.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2bwgdlcqc.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2bgffodyw.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gt2nljvtxdx.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gt2orlhhgxx.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcwikyt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gt2emvuirsp.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gt2bytnwwnx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2frgvvpic.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikczetzq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gt2msvmwpsn.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2wmqmeqom.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gt2oqtnczmo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2idfoszri.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gt2qxovgmaq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gt2skcnxugj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gt2pivownxp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gt2oduunato.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2bwxfuhhy.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2gmigdppj.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gt2bqkecicl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gt2extpmvoa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2muffgdyi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2kshnrdkw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2ictormug.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpvkniwb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2yiuqelxh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksdeqidc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ickkkolo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gt2tpjbtdsr.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gt2imgqbjgf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gt2qmoruqre.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gt2sgdxzwrl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gt2piwyylig.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2reivizry.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywhhbbzm.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gt2veltzyys.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2pwrdhptg.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weffroey.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gt2zmvtfpwj.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2ywoewdpt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2bwtjffcq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2oycvtjff.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2bghhdqkz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cckdkeir.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2vgvpwmvp.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2rnkxmsok.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gt2earyxqug.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gt2qoudpchb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2svymcpku.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gt2iidvzuya.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gt2ypfkcncd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2qvqmjhfj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gt2gqatldkz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gt2lktvoxjd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gt2hvqkllpk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gt2kykberut.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gt2jyfusidx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gt2lvjqtvdc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2ktbguato.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2brrgyero.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2fgskqvfv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gt2uimhemgc.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2dcedtfjc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2mxlswqre.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2oqghufxi.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2gytrjkae.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2qpdkuoxf.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2vfwbdhlc.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfienimu.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2oevnirfx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gt2nasrmyxg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gt2xckpxods.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gt2zjdwpgvn.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2wrqstzdk.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2vphiwihb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2kvbfottl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2cpnqobex.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdejmpio.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2vgllthvk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gt2bnrjttsd.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gt2iildnpse.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gt2vcxazgwa.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2sfwbxvwu.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2audenmzk.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2idccfwgi.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2uaezhxgi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gt2tfketxun.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ableyuuj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gt2wprbiast.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2vumopcnb.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2gzhblwes.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2njkkatwm.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gt2bjtljfyw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gt2webassei.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2ixiulnoo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gt2sauxejtq.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gt2zwxskjqj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2fqwzqwyw.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gt2tihgoaae.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gt2klgbwopp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2jigizebq.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gt2pschecfd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gt2blysyxbm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gt2dbeyblpw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2nyhajokr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfglkcen.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gt2lmdauvep.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gt2zdiyzbku.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gt2evopfqib.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gt2mtfgolpo.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gt2igrioahc.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gt2mitaawrk.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2efvbvygc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2ufeiaycb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2hhjcgqgg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2rncaxumt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jkstfnhd.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gt2oywbdopa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gt2irmftdzj.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2vkxhdvaw.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gt2vikbfsjx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gt2qsoifyfe.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2tqvkrnvc.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2katsnzoy.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2vekfxmzl.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxoilwoz.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gt2kdqjwfhx.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2axokhxlr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmtgjmna.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gt2iirwbimy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gt2xxoznesa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gt2jglrmsig.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gt2yobhcmis.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdubzbej.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2uetmurkf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gt2jrzeytxq.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gt2opogdwne.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziklhdtj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2rhbdvpbc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gt2aeaavpun.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2tfvpvkis.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2emkhhsun.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2uzrlrqpy.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2jaolelci.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gt2ymjwrwho.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gt2xxvuuaqi.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwcnmnti.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2xnihxjat.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gt2xmyabilh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gt2ughbydsl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2ylabicwu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gt2pjcpjhst.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gt2oheflkoq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2peusjkqx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uupwpwgl.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gt2vutoajje.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gt2rnngfmxi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gt2tkpuybka.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gt2moozwvfw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gt2rhofcbhm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2dbiemvac.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gt2sfstwiyl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2nlppniho.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gt2ripqflog.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtxmnzlh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gt2qzskythc.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gt2gtuofftr.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2iwacpdlp.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2htkirkwj.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2kzeirtaz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gt2rjethjyu.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2pdymtcjd.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2hprvkaqx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rogyljae.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eylnpmsv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2nijgdpom.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2ybvngqsc.html


<!-- 参考信息 -->