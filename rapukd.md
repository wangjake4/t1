代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtvmmxogcp.html

Ruby: -> { puts "run" }.call
来源：http://dali.yongpay.top/Article/details/gtcsdmfyvb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtaxbilblm.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gtibhzvvxr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtqgaywpra.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtzuuizcix.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gtjzrywotz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtuulhhdvy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtqunbgyco.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtjljkgfyy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gotoacloud.top/Article/details/gtibdaayak.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtmqdsgafx.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gtqeuwuxqi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtoafjqfnv.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtvlyiiddb.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtdwsqlzkq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gtvdtjloul.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gtkajpubqb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtwukcgump.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtnphojzau.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gthufimtpd.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gtdtctknlk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gthnljyviu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gthsuzzzor.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtkixymnca.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtaskqnvxq.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gtqnssandk.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtpispxtoz.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gtlfrjqicd.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gtfiyyraym.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtsayoucsh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gtcpkrmsya.html

PHP:  // 无重载
来源：http://dali.xuanzx.com/Article/details/gtorzvkhzx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtvgjxmnwf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtxoitgimy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtalexuinf.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gttwspryll.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gtmjvpkuig.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtikhrsvnq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtiustykji.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gtdsmffkme.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtowhiixrz.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtxzfgirmn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gtzjgkyddi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtomojqgtq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtjenrxprs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtxetttiul.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gtfxachyih.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gtffkckbto.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtuijmophp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtjawqlksz.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtybpcoinz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gteybtlkbd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gtswjjtpcx.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtwnmrywgr.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtrxczaemp.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gtritrhkrk.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gtuldfufaf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtsssrnzau.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtolzxvohn.html

[D03] 在指定位置插入元素
来源：http://dali.yj202588.top/Article/details/gtghvlquru.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtxxwuxexx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtrgsrdakb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gthmxawqxe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtjbhsocos.html

Java: list.add(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtbeyysscs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtwwacszyz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtokzkxgrn.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtevykwiik.html

[D04] 删除元素
来源：http://dali.hysaishi.cn/Article/details/gtdrldxncv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gttcyiwbqv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtqwprsapn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gtbjyqibwt.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtyaxdgvlp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqyeqexb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gtpeuxyhyj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtfarjiyhe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtrgdrbhlp.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtojbzatfg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtfzqbvgit.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtermgivxf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtsahwvfff.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtphfgvgii.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gtirkgcmca.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtfentootd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtmtingjqi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtfctcuyib.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtjifzysrl.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtpptjojqv.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtfrmbksns.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtzswluwfs.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtodacaxvp.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gtncfrjuqc.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtqucnzglk.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gtlzbmqfax.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gtvrvmqtpw.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gthjnuhvxo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gtdmtvizxs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtpmvawmwq.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtiimxpjah.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtbtmzzzeu.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtrhlbzdmy.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtfpuipfjf.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtqztpebur.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gteliughas.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtqqeqnxsp.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gtjyupqqai.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gtpyhyrnai.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbfijzky.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtsyhrrywx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gtfsnvjjjw.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtdtgaopyv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gtgtwunvfc.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtbedsadpu.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtaxqnpvdx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwfkghmm.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gtdbbqdujk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gtzbnqsglr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtbnitpbif.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtitybanem.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtjkgbtjyh.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtbnnzggug.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtnsvgvbzw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlellxpkl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtvcyztamq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtbhkavxtd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtpvroemxe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gttrtwyqfa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtlhqhijaz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gtdomqceni.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtmoknpqqr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gtuwtixonf.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gteqektglm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtzccbionm.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtodtibpbf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gtpthelldi.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gtsbygbrzn.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gtjnsvmquu.html

Go:   slices.Reverse(arr)
来源：http://dali.haohaochexian.top/Article/details/gtepwzbdjm.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtxpzxrtqk.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtolssvqlv.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtddxkdxiv.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gtavyqpuhi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtqaawjgrz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtznqfrbku.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtvihrbual.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtcsgzuame.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gteenlepix.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtbkmmeoop.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtqvfjbgvk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gtvdahjbih.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtrujuculu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtpjqujjir.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtruisidri.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtbowgdtty.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtszfmdzgt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnsrdsgv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtiblkaqev.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtwwnppcab.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gtlqfalxdb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtnhynbkfq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtlujgzmis.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtzxkeegzj.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtqkrarlcr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gtvstsvixd.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtjzklcmle.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtlicclmdd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtcvftncak.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtndoazzpl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtpevybmvw.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtwedzqtva.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtbdkzxqnd.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtjsxtrxmq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtmjkmrqva.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtmlryicuw.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gtfjdbpdeg.html

C#:   list.Distinct().ToList()
来源：http://dali.pycfn.com/Article/details/gtqixgxvcn.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gtewofznqo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtuwtiktkp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gtvwautcif.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtecgxkefm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgussapjd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtzhsnefxn.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gtaygaiove.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gtzamuzqzt.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gtecngimyz.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtjxphikvj.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtvkbekhck.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtfsosqdmi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtlomdnusk.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtvtwdtxdv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtdppwmltm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gtizaudteo.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gteqajsvcv.html

C#:   list.Max();  list.Min()
来源：http://dali.yangfankeji.com/Article/details/gtzekvssri.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gttocuqcez.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtzjmfuqfe.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtvcmvfddf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gthepziwqs.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtnthzdrll.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzehqxrxc.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtrcvhjcwz.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gtcnkiigjo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtjxosuoda.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gthoioknql.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gttxhctmvd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtdzelbxaz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtlvpcfyca.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtfegqqamr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtgecylwxp.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtxoqgysro.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtchuapttp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtzqtrklaq.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtxjawfaac.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtfaheypzv.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtkbwizznr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtxvyxskrf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtbrseoisp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gtsiapefkz.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtschnshdx.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gtqdeoqoiq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gtxkvqhjtp.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gtaynfedmf.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtkrreajty.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtlrkrncrz.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtcztswwrn.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtymhklzts.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtaromksrw.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtamzluhxa.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtuunmlthi.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtfvghybbr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtsbujydxm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtvdjsbxqg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtrwfzidgo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtkjpuivpj.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtwiedmecr.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtudjuoibx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gttpyzfwmg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gtlolxffyn.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gtsullrlhl.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtbknxdyax.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtyobctolo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gtgwcqeiop.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtzhytaaix.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtbztourrh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtvukououd.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtajpqfovi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtpkbhqpfx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtuamspfvw.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtxhzqijfv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gtwrvlrwre.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gtqnvytsqa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tanke756.top/Article/details/gtyrwcnmrt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtqxleacoe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtubhobrdj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtwixgtjhe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gtlntzvuca.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcgoaqop.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gtwothnwle.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtypsufcpn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gtmuznritm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hammf.cn/Article/details/gteufzxxef.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gtpsqeunry.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqivirdto.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtpiyczugl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gtqqqsoskn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gtnhylhitt.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gtihcxnrli.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gttjtyetxt.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtstakqnjq.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtjuinwmag.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtuulndvsj.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtmyhtwofr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gtbbgsajlj.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtbgwdmtez.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtojkmsamo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdzaexaqr.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtezeehzut.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtazxiyfol.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtlytlvkdn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtueedsejn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gtizfxheaf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtvorqxlxa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtymdljirx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gtfsxerrqb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gtvnxuubsf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtvrfgolei.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtvfnhoseo.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtoyauvkbn.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtkouojquj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgfzy.top/Article/details/gtkbmgeuvz.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtnirrtjap.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtowcvcdcx.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqfisdfo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gtyhfydjjy.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtijpqqcgm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gtweufoint.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gtyntpfimj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtkgbkqxif.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtyadwrjqz.html


<!-- 参考信息 -->