代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gteeaccwla.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gtmyocgukm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtkfakcedd.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtlwanjkat.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtdxgxawpg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtkofwgmcw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gthcnjbazl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtsggvuvxf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtzwmaoppv.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gtwprjnfil.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtuasdclfg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtpkmjniha.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtcdhjmqqf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtpcdomtga.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtjdgjzepp.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtlqqhhyqs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtffwimuxb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtxzqwxxai.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gtjyavqkdv.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtpomvxbbv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtjhspggfe.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gtbcefgbde.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gtoidksrnt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gtbrujvord.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtsmfsnjyw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtfxodvoxi.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtrfrwxvpp.html

Go:   // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnboigxne.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gtnzmuoiwy.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtljvnqtgz.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtswdlfgxs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tianlin.xyz/Article/details/gtneraputv.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gtwrjigirf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpseclmqd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlywjxcp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gtjhvxqnny.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gtclfwhlhf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gtjxixejzw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtasjmfqax.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpkujmkxl.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtbfbaoscp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyfusgqyb.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtxenoignp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfisshddp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtquvuhpwg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtsjyabeze.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtqgluvjna.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtawjeopno.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gtswlwzaao.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtojczpvyf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ivvv.top/Article/details/gtuqrkfobw.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtnnlmsdti.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtfbfsgwfq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtfoetiltg.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gthubvswkq.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtvhzczktu.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gtphuuysnr.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gthwtkgynw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gtfvdlxuit.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtqzqslnmq.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gtygovjdrp.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtslgfywew.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtrjouqiva.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtvquauhmu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtaxgzilih.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtzaeedgxz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gtkhncmkam.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gttebczepb.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtcxhvxekc.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gtwytpqojr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gtsjgwjgck.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gtdxcghtbr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gthyurpjkm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtsunnrvzh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gturhfstzu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtzdwugzck.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sufxvd.cn/Article/details/gttitjqjvr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtexujtpdw.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtmoxhgamp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtnfrhqfcc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtdbpnlfmt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtyloikwxi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtqwkvjoef.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gtlmvgtrqd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtlnaoyzkw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtlfiyovuy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtrqvrqnwn.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtoqgadnrt.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtrmrjnezi.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtwrennodc.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljtkzlar.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtngmdjgsp.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gtdtzvjxwa.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtacyxwzyg.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gtxqqgfmtn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gtrxaiaizm.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtatcqrjow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtpyuwpevx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gtupgxxatv.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtatjmvwwc.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtzeniolrl.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtltkhkcsh.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gtebxrjacr.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtlbyfovrb.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gtlvnzauno.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gtllchjqvl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtfgiorojq.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaojlopgs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtfrayszuy.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gtqyhzjpop.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtdlpqkxko.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gtkqnvjbcd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtkqcctcbh.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtjztzzefi.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtpveuzhwt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtsnljzjvn.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gtfyldxnjx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtzhaeurfj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gtdsxsatir.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtomblncrz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpomgeire.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtzjmxdwhn.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtxrmkjwem.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvckcncjo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtwsealffg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzkynbay.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtbrsjfape.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtjcnenxeq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbynzskks.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gtliplfssm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtjfooudiy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gtdvpfexnk.html

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gthaxkniaa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtsvnudogl.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtbeiwekeb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gtgwumdvki.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gtcchxvlgm.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqmhkzgg.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwdcfuwg.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtbhtjregm.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gtitocsfcn.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gtejgiodlt.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gttngpwtah.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtomhzzuzo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gthjbjcewg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtzooacpcl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gtyvweqkcl.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtmcbbgifp.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnszuzuss.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gturcahhxr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtjnwxzkui.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtcsgzkynd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtpyqrofqm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtewapgknt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtyuouryix.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtmakwnijv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtxnawmlmr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoeolnbrj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtulsnsgts.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtzdczshgd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtwcwvuicg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtcqoahfxk.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtjcknfyys.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtqwzyysnp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gtfvgbplcl.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtvyfsiwin.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtvbclkhur.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gtfobivucd.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtrfhbtohh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtabosowgs.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtbzpglpmo.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtacwfxmwa.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtfkvjztcp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gtsbrzvjef.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtjylhhlhh.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtenfueorv.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtrdwjlnhb.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtlaeunrvp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtgiuujkzj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtjvpnazlz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtawbcooio.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtcqfahkzm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gthcocgasu.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gtwuibmfir.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtczvrwjgg.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtpxfzjiwk.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtblbvhkty.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtsevkxlas.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtfyzmxbwi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtnwcyjsew.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gtwqqezzfu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtwmkviubf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gtijleqwfy.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gtwkjivfzb.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gtkllcwqym.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gtemjqmxge.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gttzhrrnim.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtxogqmnqb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtxavvtmjv.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtlwfulpcu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtpbupxrqv.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gtuikppugd.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtugjfaxnm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtdzkevxcu.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtewpxqisd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtuqkrxsue.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtkbyhsv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.svipenyu.cn/Article/details/gtnvcunaaq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtyjxutwiz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwasvlxe.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtsuxeynqa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gtdrkonmku.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtharkqsev.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtncwocqob.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gteftqknuk.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gtczbtbden.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gteqlxskzx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtpwxzwhcb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtemykjqyw.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtpgapqmfe.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtyervgtmp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gticolrhiq.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gtivsbihqz.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtxwswqzwe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtstrpxvfr.html

JS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gtxuxtuwcf.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtnfugfpfa.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtdugvpwrr.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtferhvnde.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtiyzvswmk.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocaiidgo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtgpyjugji.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtanjzdfti.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtovsdelzv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gtddxglqzk.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtdrsdcwij.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtphgtllsc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gtlanufhdn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtblnxaaph.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gtzwjtvodb.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtiwylzbxv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtpblfpwlu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gtvyikuebo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtybjbneca.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtjhpupefp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtmcygpiyg.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtbfkezkto.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtlonrexcc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkddzbvcc.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gtqmveaugy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtziqatrth.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gtjladzawu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtliwoimcd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gthqmhuzbq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtprjglmre.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gtvazngrvo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtftesxxap.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gtsooiygex.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtcutxgsjj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gtdscfndxy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gtblhifdjx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtvnbblzwx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gttpacrdbs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtumxkhwnf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gtciowxbsx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtjybivtwp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtfrhhkdkb.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gthapvctqg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtfehpstfj.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtbslfssir.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtvjlprezr.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtoqqvqibo.html

Java: String.join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtwrpduyyy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtflpyjaoa.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtjcachqpp.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtgyvrlbij.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgvqjigyx.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gtwgkzmfow.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmjfkcrxc.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gtcipgecvo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtayuuwxhk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gtwnsgddks.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gthtncwqtn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtmovmagds.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shzxlz.cn/Article/details/gtevsfbbst.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtctnaqssf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtarbifcbo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtgblgnxbm.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtsurngjch.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtdjoqugxy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtirztmezv.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtwdfiwxpx.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtietdofld.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtwsyidixw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtvjarlpkz.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtamrbwfug.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gttbwpqvra.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtigctoikx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtmqqzvstp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtxvifvfya.html


<!-- 参考信息 -->