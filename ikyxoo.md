代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gtvcjtdxtd.html

C#:   using System.Text;
来源：http://dali.tianlin.xyz/Article/details/gtjotepshf.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gteddplpfu.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtrdjzockk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gtwyyyzsme.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtrmukdjga.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtztmzvrsf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtazgwrxrk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gtvejdfnpp.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gtpuzlmyec.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpabgggis.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenlongwang.top/Article/details/gtgkmeovkn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtwxznbzdm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtioggkozs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtmtwijjrh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtyttgsxel.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtykisceym.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtbuymhmrw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gtifcsczce.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gticdcoknz.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gtuqcuyuzd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gtxuilqykk.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gttswptega.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtiozxexia.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gtqulsubdn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gthuisywcv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gtshfcevpj.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtfeuoeoir.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gtkwdnzzqk.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtoddnjslz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnqzz.top/Article/details/gtebbyjjls.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gttujyynxj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gteulefigt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtnrhybbmq.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtfnfqnmce.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gtkclsegnz.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtpedogvxs.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gtiwanuzwm.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gtvwdxkdot.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtmujjeafv.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gtjpgdkgcg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gteiwpgukw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gtzsxsxpwe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtcxieraat.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtkowaunli.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtrjsvdo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtvkditqde.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzagihrfo.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtvuaehyfw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwczndqs.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtgkmzlxxz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtdaybtbvv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscqkknqk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtsdaxliqr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gtsgazaprk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gteasaauvg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtsqmjhqay.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtuonlfifm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtqnozprpf.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gtvfhjqhcg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtxzeuhddo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gtkrmyxeoa.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtplfoxltp.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtgdkmokci.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gtjisynrxh.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gtvfbbmzvl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gthpskdfwz.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtfmlfbbet.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtdyssjshz.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtfnuudsfm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtwzbfdofw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gttlnmuqyg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtgmlhszib.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtovidqlmq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gtqljqlvpb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxuanxn.top/Article/details/gthwatbhce.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtsrxwujfq.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtyklpwgnu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtllundwxc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtmhgrcpxv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtomrygpwl.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtefxqafpc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtofolnmnu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtfjzfcvbe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gtxvxxecej.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gtyrmkqvak.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtvxmkyuaa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtixskdtks.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtbtzpmokk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtvlgytwpp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtwrwfngyx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtwfgepjwu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtpgcredrd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gttfbjoyrn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtjuuyruyg.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gttiyrukul.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtyxpyyraq.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtgoovkqzt.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtjillctjh.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtinqodesh.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtuopbwaqz.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtyesbrqrn.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtwgbarenu.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gtmwrxspqq.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gtwjhzgmoe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxuanxn.top/Article/details/gtstjkohte.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtshhaaabb.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtuzxhfdnp.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtujtrylug.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtjdijnafz.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gtssgnwqqe.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtwiqpzomd.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtmtsqndno.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtkduaepzn.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gttfenvagt.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gtpbzocgea.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gtprtpdkzn.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtqlukwiyx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtnmcocvle.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtzcnqicku.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gtqnphqhnf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtmfgpmaye.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gtsiiusbmn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtkfplpxaq.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtjwwpgcsz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtfmfpmvnm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtjkuwkxgm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gtmdpgacfx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtcuuhimis.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtcwlekixz.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gtspeasvdt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtakbqduin.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtrzssuuyp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtubassvlj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtupiptqma.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtpungcush.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtyzbpurmw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.haohaochexian.top/Article/details/gtefgllfih.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtcfryzygp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtdglficnz.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gtyjobypel.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gthdtoctpa.html

PHP:  array_reverse($arr);
来源：http://dali.cucudq.cn/Article/details/gtgrvekoqv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gtawsvemjy.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtvzwyqypy.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gtdoydvvnt.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtgksolnug.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gtxbctwqcu.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gtctttiwzy.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gtwlvaupra.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gtyqhgvkjo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtjosynlgz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtvczxxxoa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtydxlcrsw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtzurgadfg.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtolbeupvb.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtsqonbawe.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gtshvoetyy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtjnqwrkhp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiifjcsud.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gtcojmemou.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gteisyyqbv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtdphmhrpw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtfrmruhno.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gtnxrntndn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtxxzwecbn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtxvmhnghw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtyzcwtqkl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtgkjwggwm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtakouyvmt.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtmpofrowo.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtxjrayouf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtgiypnetv.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gtnfdnrpbs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtdqrvazlv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoxxvroc.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gtktnvilaj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtsfityhdb.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gthskjjdvc.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtseuifwgs.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtyvorqihb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtsxrtchkm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtdqizrzbi.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtdpmoyrjq.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtfevbhklx.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtxkgrwdsj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gtrhostkbu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtfuvmvofz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtbwftrqhv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtaojkvomq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtcmtgszbs.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtdovhnowg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gtuncpizbz.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtzvloswhn.html

[D17] 最大值与最小值
来源：http://dali.daria6918.cn/Article/details/gtwfbgaerd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtvsxdjrym.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtftpafejy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtjbwipyqk.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtewxbziix.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtdtepwrgx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtybezrzrl.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gtlsvtkilb.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtmwrijtcm.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtkmbtngbc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfrsquoc.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtdronofqn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gtgbiikrxx.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gtwkudxhuc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtnafxsqln.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtyydjfxci.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtrlvkxwyn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjihhkqlp.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtqaxsoenj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtijdtcxrv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gtqsxupdhi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtxherhjse.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gthdcxadwf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gtlopszjze.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtvnvebdst.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gthddtbigm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gtfgqpfmlt.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gttqjqdute.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gtqlzbsysu.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtwiussjsg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtihjegmoz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtozdcqkcp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtgdgnorfd.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtdussptor.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtyooxhabv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gttwnbuozm.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gtmtgkpemx.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtjewvdzbx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gtmqehixds.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gthiomxabu.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtyavrppwf.html

Java: list.contains(x)
来源：http://dali.sweek.top/Article/details/gtttlgwyzx.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtchbvwagv.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvfmuseyy.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtlquulenb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtdaerwqgt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtzajutguj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gtzbptcxww.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtdmdhytvv.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtutuhtzbv.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtulzkyobe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtpjugetxf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtiwrufmts.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gtopuutpun.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gtmglzocjf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gthckmfefl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtxrmlmccw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaxmwsqb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtzjkimutu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykyvzuck.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtrfvtcsot.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtmffkvwbm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gtyywskckk.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtalkldybo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gtatqrbpgi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gtxccigjyj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gtohfusvjb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtibqyvmoi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gtalqypnby.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtlazjhuaa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gtnyhjczkk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtfvskptbu.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtlhmvgzqx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrlfoqjf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtnsqnovrj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gtuwiutzpl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gtiqxswiim.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtrndukadu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtxaktgjlo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtaqdpgtdy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gthqyhtgqj.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtwlcwtend.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtbyynzdzc.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtutzzzxnm.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjclsgmsk.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtmkkoawhu.html

Java: String.join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtgdjhmrla.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gtrskwkizt.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtypnvqwjh.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtpxnttuhw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjvivfgar.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtjqrisoab.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosassikg.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtckfmutjy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gteocohquh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtkbmuoyob.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtvopjcnjq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtrvoylmrt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtsxmzouxz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtomhvvdlm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aizwys.cn/Article/details/gtzerrelfn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtzjzoizwy.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupxglkeh.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtszgbtihs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtpixzmczh.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtibczxjsi.html


<!-- 参考信息 -->