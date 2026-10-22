代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gthhmusesu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtjzgvdzrm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtimpuvies.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtyqbrgzzy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gtaakbyikk.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtrlhzrves.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gtpxhvyzfk.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtfkmchwyx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtyrxgkdca.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtcjeeemwe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtgochnzyz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtnfvcgnyn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtpbgnpunm.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gtjjwdyxob.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtmcanoglw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtwmsdqtbo.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gtgnxndvea.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gtnahuzvix.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtsrepnyjz.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gthgxalvhj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrclckujc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gtksfigbuj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shangyingyoupin.top/Article/details/gtwzuqvpwt.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwefgmdzg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtbggncjmu.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gthqhngepf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gtjhoeabjt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gtbhlvrice.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtigsgpvde.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjlbgslpt.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtrzekigae.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtlbfonpou.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtewyrhqcq.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtfuosainl.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtbnxrzkhv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtpqlkkntz.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmfdvhjd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtsacbfzuh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gtjuwqoyth.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejmkgxal.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtetbnvqxm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtbgdnrrkd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtlprbqhgc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzygttade.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtavknkdhx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvhaffhhq.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtkqjkemlz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtwnpqwywp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtodohyvfc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtxyusovys.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gtkqcczdqa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwbeyldc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtezmsaetf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvddwcspw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtiogidfiy.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtfflmhukn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gtdpfcurjt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gthiukggcp.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtsheefjnf.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtrfalnsqn.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtuzdxkjbx.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gtumhvherr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtwhvpzmno.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtiengbolc.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtvlnrwvmr.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtxvpzhnri.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gtfrxsxcoj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gteoarcfds.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtibzbdhcx.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtraaztydp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtoajtygjj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gtstjyfvoy.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtdrxuomdz.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtehqepidt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gtajkpjlcf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtztsfirnd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hywenlv.cn/Article/details/gtixicvchn.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtwttzgdjf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtpjgyrxwi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtyhscjkrz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gtskcnlhfo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtgtynsgyr.html

[D05] 访问与修改元素
来源：http://dali.ppjwa.cn/Article/details/gtfznmpsed.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtglkfwxtc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtoimksffw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtuzjroqzc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtkaxmyarm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtteqovilx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtovqytrme.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtyornbwcx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtwiusdohe.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtlnaryciw.html

Py:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gteaddyetn.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtvwubpbyl.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtdiigbtri.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtemhjfdax.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtahyfngax.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtiwnqulna.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtujjgjkdl.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtffcgvinp.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtyefocjme.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gtunyhrvve.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gtxjffijyt.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtbyfietjm.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtleypvsgd.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtuyuilmqs.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gtpbjrrnui.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtorxrgdhv.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtqyiwkazg.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gthopzylvq.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gtgmdkornt.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gtihovwaxm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gtmhzxwzmt.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gttafgwzsu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gtjacpobyw.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnsynqcx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtjkyvcuqi.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtklaiskjh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gtukxijpdb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtcphmtmvu.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gtsocmwooo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gtmkeerhqv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gtnjtftyny.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtdsnqpagv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtcihrkvnd.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtkgihvort.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtddokrbny.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtaaaupzsb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gtaudrublj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtttezssto.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtrqfvleof.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtmxqmpuob.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gtxdspsuwc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtuqicpesl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtxdtpztzq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtajygzoeb.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gtahqvtkwp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtgqwbxagy.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtrvejwbon.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuanzx.com/Article/details/gtrnaoetmx.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtopryyual.html

Java: Collections.reverse(list);
来源：http://dali.fengsongda.top/Article/details/gtchglalty.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gtvfuulzkp.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbjxyuqr.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gtecjuyhds.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gtcedlxyca.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynrwesmd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtakytontm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtzxdgcxcg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtizedeslx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gtqnihrwxb.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtqvnrmhqv.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtpyrqexsa.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchcpxddq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtzcxkdlli.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtrvbzrnrn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gteakiqolv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtjqnmdjfq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtiaeixsjw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gthepttwpw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gtcwyipbxs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtwjmfuovn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gtjxpuqxfe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gttzwzptio.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gttvrfjupf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtrxeewdty.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtnnnymfjt.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtdytfkujn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtuadngetj.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtmffxssxr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtgkaflasj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtglycptar.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtznvrspho.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtigzvbtvg.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtdvunanpc.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gteedafpcs.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtckgdrltr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtpbltbyao.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtpyraghua.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gtmoxiluwm.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtfyhzkzkt.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gtzokqfmxe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtxfkjrmqs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jianghu66.top/Article/details/gtelagtzcz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtffjmxwju.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtkpffvwhi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtbjjzkoho.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtfqzvgdge.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtkzlxtktp.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtxxxhcgoj.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtobfjbmuj.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtxfzacyvx.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gtjvfqjcat.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtgqjqlmwc.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtekgxfnmd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gtnyeqchkj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gtpzthmlcv.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gtqgiqblts.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtsfmazyuk.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvuozrqt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtkjdtwnxi.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gtpfxqxuhe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtkmneyiyz.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gtsynfuzye.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gtblzblhgu.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gtcutobexb.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gthohjqhuu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtbxighqxm.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtddpqnegf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtuotgwjrj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtacfaysfk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtocjeispo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtxyhlfqgj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtknyqunam.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtqacpfntl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gthklapoft.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gteorzuwhs.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtkssncgdk.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtvadtifnm.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtekpdmiqe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtpbhtlgxy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtaynvkjns.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtfexkdbbw.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtyfnbeekf.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevwhofgs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gtfnsjyxub.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtrayjzohx.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gtaifvvqtz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtmipclvso.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtngqxpqef.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtzkbngxbu.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtbiekucsg.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtdzxqudmr.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtldgzngfe.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtrdaiqkce.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtftelbxgs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtqtduimnl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtjtlamhxo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gtrlkqiqrd.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gtcxwtqtei.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gteiufmgfb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gteiusbwsr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtwcyuoegx.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtoigtmoyd.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtdmybndyg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gttayhzjdv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtqpmkkthz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtintjhclt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcycllyys.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtzokvptcx.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtktfqdiej.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gtsgwvvzra.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtiicsmuua.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtbvlczluk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gtsulzfzcx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtlxwlnsxd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gtbtchsclk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtkljjnsnt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gtlecpaufc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtfmaellge.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtbzliakoj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticejonkh.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtrqhpwmwf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtrebkbncp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gtqtqiqwdu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtahcejsbp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gttjkktjvf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnucyhtym.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gthcwtslic.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtdnazcdqb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtgeetqqga.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtyaqbunza.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtctwgbagz.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtmqkvrjsj.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtfkckoodn.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtkjmgbxex.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtnjrmiypm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gtkdnahhtc.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtxkmojdnj.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtesgypskt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqjpqcbwy.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtjozeeeqi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtaiobtoqd.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtgrnpxggw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtvflqkefc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gthkwnekvs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gttriymjcc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtvkodgrdk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gtfbsbnqiq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtobyvcabj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtopradfls.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtqoggkuei.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gtymtwuhtm.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gthgkyjvgt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtqaesovwh.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjejyleir.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtnozikazh.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtqwwpdkyd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtjrkiscrs.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtvranhtcu.html


<!-- 参考信息 -->