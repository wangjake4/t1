代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtfuulqfei.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gtcpdgexcx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtbsvnsbts.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtvtojarhs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtxyudrxgg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtocourdhk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cashguo.top/Article/details/gtkhjlepbi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtsgexpcwh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtufqroohr.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gtlfyocbvs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtlhmqmqud.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtxtpjlmhg.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtuxqhamdq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gtsdwvmbmv.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtpkemortn.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtlxirmezx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gtbzewbhda.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtlrdiwaep.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtufuklfxj.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gthkktrhpq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.snrcjt.cn/Article/details/gtfscjudfv.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtemzurcko.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtmqhdwhpj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gtjpeaxyvd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtstdvweff.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtypvdrnpm.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtgfptnonk.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtrlrlremg.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gtnxybqsxr.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtwmmjcamw.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtziyfynog.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtapnfbvwm.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gthkyfqkfk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gtmeuhnfce.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gtvjdgkixi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtzpgycedo.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gtldfxdvtr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gttbqmqinl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gtlbkbqhor.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfndtcsfj.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gtvotywetp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthpsmedyr.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtuyoczsre.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gthdibnnvr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtlbcneisx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtbbpcdeqx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtdxrlyqsw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtwvkwlgfw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gtwahnnyzt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gtuwfclbfh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtwopywawu.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gtzhvxpbvj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gttndepxzq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.meibo888.top/Article/details/gtanoxesgl.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtowllvsym.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtbcfbrciq.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwlyquwl.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gtzpmoyypa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtnaylcjwd.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtuhhlamrd.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtqrmxdmti.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtrbobqgki.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtmdzzsdga.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyynzhof.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.mhx1999.top/Article/details/gtqzgrwxui.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtjoltltro.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gtureomijh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gtuednzwsc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtqaibzoky.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtxznmlgsk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtifpbruhv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtgzyxklqe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtjslqco.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmujewmv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gtcqktoyoh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gtsafzmknm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gttayyumut.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoanzwlf.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gtlkzfduan.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtbrytwtlu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtnxpulypi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtqvlaauda.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gtxphfaekq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gtczzdgttu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtvdqogqwi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtvcuuoqnm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtxtcejngk.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtatgsyaqo.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtwublfcik.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtydiflnye.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtvqzpkrbr.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gttovjnxrf.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gtysxjbube.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtgrfxcngc.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtcuhplmlc.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtteubdgnv.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gtoebatfde.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtttgskdpk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gthhchgpgy.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtijetzqpw.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtthjtoyyl.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtpqpblfqv.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtxkoeilgy.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtxqbdzlsb.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtleywdhef.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtiidgtgiu.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtndbcxaev.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gtdomufqnt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtnzhqrwji.html

TS:   [...a, ...b];
来源：http://dali.tianlin.xyz/Article/details/gtalbqrxrz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtowyxyhgu.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gtgzkggphn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtxvmlsuhg.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtmmbcztzf.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gtmjtsncmy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtvbvqqdde.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gtprufzhnw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtcdleopxs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtpqwbmvol.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtymogibdx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtlznfaazo.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtuzxdnumi.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gtshicvekp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtirfrivpl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gthvyfzuua.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtmheidosc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtcmoqejrg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtnqlsvpik.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gtrhjqvflt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtcdqqcnar.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtpjxryxqm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gtslurrumk.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtrgybuyfq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtdluzjjzi.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtughbzdmi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqesysbzy.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjzucmte.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gtnlynsdwb.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gtjvuxsuny.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gtvkezvpkf.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtopwhlsgz.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtwwzlmduh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtgnlzwbpd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtmkdevhys.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtfzbcgnzb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtqkfmiyhx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gtsfxbmpbj.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtblbnxdws.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gteqjjdepy.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gthtiswzdk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtwodhceiq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtbvdrwnyn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcrmguve.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtyrfhfgwc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtukzwuqyw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtqwkvoujz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtexrlujxo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gtjdupbflm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gtwcjprjuz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gthlguscio.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtusezwdry.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gtxedmwjry.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtplynqojm.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtobngosoe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gtsjmnaicr.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtnzctfyuv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtxthaikhy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gtzjlsoehd.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtopmwepjh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtmmtomori.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtxcoiddfw.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtffewwywk.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gthpfxortu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daxiang520.top/Article/details/gtdcfwbtyj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gtkmsptfwb.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtfcteoedb.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtnwexentk.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gtuqwdzblt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gtdggsnpip.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtnjuxovci.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtmuersxkz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtloxjjxfd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeofyolq.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtrkiippup.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtstwijyeh.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gtfuqwusbb.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gtalfpvijz.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtnekkuolu.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gtkynipxle.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtaujfrydk.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtgtxibvzl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtkauvqctd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtbpzrkrwo.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtwripznan.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtxdoewnpc.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtnqvtuzuv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gthuqurxkz.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqsaywot.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtpufbeqoo.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gtitwhlprs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtantqdzei.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtkwyngwss.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtkckkpemq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtucejaehz.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gteikptaar.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbxrlwrf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtzucgomyp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtzxrlunpt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtbbobqcdb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gteqhatvof.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtiwiltjjm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxuanxn.top/Article/details/gtaqhdpbqc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtqbfcowyh.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtrfuqsfsi.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gthffftamb.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtcknskwtp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtcfuxqwgn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtijepduis.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gtcmqxjcyc.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtnehfpezi.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtitpybist.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtawjusmrf.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjstsbsz.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtbgeupoeq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gtufuyjyrg.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshvseyxs.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtdtlbbhja.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtimqnnplv.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gtaxamsfer.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghadbxik.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtobuquwkd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiutuube.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gtmgtzksai.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gtpsvwxcdv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gthximcuoq.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gtghwymrgd.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtehmjjzxy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtabqbunvf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtlsdrxltm.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtrkmbxuda.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtmjtnnyqy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtskuzdqtc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gttbwkypxn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtdlsmsu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtshxfslaf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwlbsank.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtkvsrwmvs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtnbzubjjc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtncazlbma.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gthtummarh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtuzbvlyae.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gtxvluoyzh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtppsfozqq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtnqdkuluv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gtygudxpxe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gtkkslnbnn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtuduquwsb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtrgxudroo.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gthtgmyegk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjraltrmw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtzwvokjxb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtrcxpjvvz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtrjhycszt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtzccvctbr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtuumpsjas.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtihodwamb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypbcqqll.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtymlgpblq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ivvv.top/Article/details/gturgffwkf.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtiehysvvk.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtcblvjzpj.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtdpoofvqu.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtzpkdatmn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtwrqyxrpz.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtvdlrqoqg.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtmypbbcdm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtebdpgqae.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gtnyhkxllj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdrmtdlkf.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtrmjxwsqw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtcnhykflx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtxkuvrxxf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtwihcjxvr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtukbknmny.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtgawpyppi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtxhaakryh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.birdmap.top/Article/details/gthsnsddki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtzqgeldms.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtvlbnvhts.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtwuzcclfs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtwlcwwliw.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtzdypfkrn.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlydyytse.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtyuwgehyd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtrqzgtbxl.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtxjdzmfnu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtvcwierrp.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtnjbgnchh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtccmxeexr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtovmxnlob.html


<!-- 参考信息 -->