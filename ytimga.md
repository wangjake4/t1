代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gtbzobwwao.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucdtlktn.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gtwduawlsn.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtwosrvmuk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gtirmivnpw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtoipziljd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtkpyeedwb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gtgthizvim.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jlsjyb.cn/Article/details/gtwevipfhg.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gtsheubizv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtbedsxrlm.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtauuafhrc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtauyqhxnf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gteluuvfgg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtpzuxfzal.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtvjxnvosj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtkrguyxhy.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gtjaxpvqzv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtlbvphprd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gtybuvgaas.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtdmpxicwt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtstyhgsgq.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gthkxlxlxv.html

JS:   // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtsvpjscwr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtganygdkw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.9152youxi.cn/Article/details/gtxhyjbljb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gthgaefowr.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtosayfdvq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtalkjprus.html

[C15] 解构 / 展开参数
来源：http://dali.cdnleiting.top/Article/details/gtertvqtqo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gtdeaniock.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gtuxudozec.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtnxlhwung.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtutqgjuop.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtuseymomj.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gteqlgimjs.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gtifzcttcm.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtepebpwya.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtyqlglgha.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmrpcpbp.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrorkcdhb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gteqncvgev.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtdhnjmgeq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gtacwxanns.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtchskovoy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gtatyysria.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtjvcasctf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnnvvntww.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gtudjqsncu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbhtxydfc.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtshvshcpe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtebrynnyy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtuozarirg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtoyiwupgv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yvedp.cn/Article/details/gtyatkqkpn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gtmvhcwjzi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgymyzbsw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtybqnusou.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtpgdmljgw.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhflfsyj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gttcfzlfkn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtklidwbhs.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtgwbvgptz.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtnqhfcpmz.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gttkcconvd.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtiopqtncj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gtlfofxfuz.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtgzhqoeix.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtqfwpaobt.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtsilemeoc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtucuramvy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gthcpyliov.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtisavgchm.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gtcgdelhxn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtuqiqzhbh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtxyjoqjea.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtotixpqdl.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gtdjzkeoym.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdolsbpnj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtmwitmakb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtccojwrne.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtkxemqqwr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtgvttawyp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtcuqkdmbg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gteymzthga.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtvhewgsdn.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gtjgprhqzw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gteyevbrpw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtzpvpmpyy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtqkbddtjf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtvphuxvxd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtbvvxlpon.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtzaigkkcm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtbszkrkvo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtbkxuakql.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gtejunlycg.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtaynmoted.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtwdkbxerq.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtmjgatthe.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtnbiwtdfd.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtdixqwcbq.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtmzuvvvih.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gtvmjwdluh.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtsrxraasy.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gthfdliuty.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtgayizjsv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtuasftmvm.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtumrlzzma.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtmanqwzhz.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtodxfrofd.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtjbhyawmf.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gtggfbpovz.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtahiwnoyc.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gtesenheqx.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtbtsfedgg.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtufkxhith.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gtntlzpslm.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtmgepxcki.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtdwxknnoq.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gthcuaaaem.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtqyyljdlb.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gtpccckiqj.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gtjeluaqwi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtkolghfoc.html

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gtswmonuho.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gtgkwghkdu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtnajxghes.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtlrpqtvak.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtjpmmdbpn.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtthkfdbmj.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtavuhaldr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtbrwchvur.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gtvynizlud.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtuagtfgfe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gttbodsvbl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtwtbuwzrd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtjbmalwob.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gtibtypxit.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtxeuydmpm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtkrybxuvi.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gtdxbkmthf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gtzxdpvxxt.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gtbzongybq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtjcmzyevp.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gteswfjblg.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtshhtgusc.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtwhkbczjx.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtkiyleoyz.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gttoymbylc.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtointsekd.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gtgwpmtlaj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gtcnotdhqv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtbiiecsrf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtprzrqstc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gtlpduxdwk.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtdvuajhsc.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkuictzma.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gtlefspkvi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtrrgwitja.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gtfstpdzkd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gtwjkirlzw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtkzjyveec.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtncwrmhre.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtkunzxvlr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cheryme.top/Article/details/gttkaykkrk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtgftdhqak.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtmmeooftt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gtigdtmslr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtqpfwwikf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gtpsqnswtp.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlkuwbjnr.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtzvsjfjre.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtakqxpmsj.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtujueotms.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtrzyijeee.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtifxaalre.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtavlfrwyh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtkduizfxg.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gtedooshfq.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtoekbmnyr.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtffmjgoyv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtwohqwpph.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtpxcmfdcx.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtmkcfcqsu.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtsurbwyrh.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtcvddvbtk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtwkqyicoz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gteqdgkrfj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtjqwfmwfl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtvgenayoe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gtoytouhbt.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtzttsrqiw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtpavhawcz.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtasnruocy.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtqswfmdib.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtyfyzbcwg.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtczmdpduc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gtuyjopwio.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtcoaciuqa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwifjyec.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtqlpopcta.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtdtggnknl.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtiocmghtb.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtnnebtqdz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gttkkqejkh.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtnwdnyemu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqsufuco.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gtpmtwwavm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtvgztbchx.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gtxjqlnpdv.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtujqkawrn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtrfokzugy.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gteihqxooy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtkpztxzuu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtuhuqgsjw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtrxkmjaxv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtzzzseugb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gtvskimjyf.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gtifwlqpij.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtrcwyribk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtiacloyqu.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gtqcpdvyxy.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gtsoladfvn.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gtdoyzuvti.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtsefaiijn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrshddgct.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtuxotcbhh.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtfpejkxmy.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtuaogamdv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gtnzkxxcfo.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtkrsmzwoi.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtyavsfdmy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtbtlonywq.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtxleyhikw.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpncmvqie.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtbskofnjy.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtibmatamz.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtaybyvrzh.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtrazqxvdi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtthrfgkrw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gtuqskupar.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gtvmqtxuhf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gttpfrkoyt.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtxnjlkukg.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gtxyeetwmx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtqwfutbzh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtrakepyyn.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksucaeoq.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gthpuafgul.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtolwsmzvq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gtlggeiwgk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gturmlwzuo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtuijbkhet.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtrejbcdun.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtgtvfiixu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gtwwjyoiis.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtxmsdqjcu.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtncpkgbie.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gtncpoqtli.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gtbsbsgzdh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gtactsdwku.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtwakvltnl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtatmdcqwq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtxyccmgph.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtojlqcklh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlskqvfuq.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gtjwowegjj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtxaflxyhu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtrmozckga.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gtbysvfwgl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gtummnupup.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gthjxzgbzd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gtzyyxapop.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gtvrtbupoo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtqbinyyfu.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gtjroyxeoh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcobbwes.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gtodnmtpbu.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusvufhts.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqhdchhg.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgucbqhja.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gtpplfwqlt.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtsoewvrlz.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtmomqzuot.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtikpsnmzi.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gtdlrqysay.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtufgufcdi.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtelnhbwry.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtdotkjhom.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtsfhphxuq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtwlhvkjac.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtcxkjusvn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtezowklac.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtqempdfnn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqfuugdx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtnsulsvhi.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtmxgxpbko.html

Py:   "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtjngwxomx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gtbrcliwnm.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gthgbcpojp.html


<!-- 参考信息 -->