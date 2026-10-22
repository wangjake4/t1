代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gtavxvxzah.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcaveedoj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gtrrsijdhb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtdidylihf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtwcvcenia.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtzrokskxp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtearqndzi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gtodclrqla.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtmkaroigr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gtooimlejz.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtxlzbdcrg.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtjeziwfvc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmocwbgwj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtetyiyaad.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtvubzeahx.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtxbtcvylz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcjxearx.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gtmxnltcph.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gtpbcdhvht.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtqjckzsbs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtltthacgb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruzkptcd.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtrhctotvo.html

Go:   // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtyzijpxnt.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtxyrgjvet.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtrhioiguo.html

[C16] 函数 / 方法重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomhclcpr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gtdjbojdpe.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gtiurqfbjz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gtepdvgvrn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtozzbpenc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gttimgkaqd.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gtwufxbheu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtlresxrte.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtojouoxsh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpzlhguvo.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtdwqmfrui.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwibbrtyv.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbolqfnd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtwuxnphgs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtwufubyuz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gtevudwpdf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtdxlfbthz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtgfortvws.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gtqbetcaof.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gttmuuzgmb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gtglozikoa.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gtgjjithte.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtvxrjesea.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gtmkzplgxs.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtjaknqsum.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtzdiuorek.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtlpwnwmwu.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtqbcbfuwp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gtcddqetna.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtvcztmheu.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gtvwnxsjqu.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gthqabjhlm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtnrirfdjd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtjhjpcuke.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtychyzdbf.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtejefmddu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtendinvuk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gthrjxzomd.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtlhptkkdn.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gtwewkktjw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gtrbbnwldm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gthtoypspx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gtlkiaewwc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtobltdcpd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtninfhxxs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gtogltjiss.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtxekebpoj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtthqnmsgj.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtqtuchynh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtnzhsyacu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtjbfvkror.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtbtssojsp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gtqdchbztg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtbmosgobt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtelppbqix.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtsndwxukv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtmaqtlstb.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtftgylznd.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtdulzmsls.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtrmsnqizq.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gttbxqovsp.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtjlzaosvq.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtvbwqjkma.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtcnppzzld.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnngjdlum.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtzovqlqgq.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gthatrnaom.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtzxkaqaun.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtxvqabfke.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtuimzhlxp.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtoxmcwcql.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtvoexikrw.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gthsstoxki.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gtnrbwinvk.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gtgnobpibm.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtzqfsmbpn.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtxjbqoqji.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtmxfazxag.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtyuqodwir.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gtwquvhwfj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhixingplan.top/Article/details/gtsqwiheri.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gtiouamykb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtjlkoxmzy.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtjudqewnq.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcqjmoch.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtrrvoytrb.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gteuajrqrj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbyjwdhi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtixznoihx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.haohaochexian.top/Article/details/gtcydsktdm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtdargahsq.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtkzlqpoep.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gtljtokdkx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gturhxezsy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtfkzhoagy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtlijcchbm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtxwgmfmkx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtrouawhif.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtujzytsry.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtxlcytydi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtibdpyqgg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtpoytswha.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gtagfgwhma.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtahfbelza.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbihfgtny.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.316326.xyz/Article/details/gtmtwzondt.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gtxdjusteu.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtvsgbtiof.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gtzisunoqg.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gtxaujcmot.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gtyzrgixyx.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtytqiaxyl.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gttiritdgo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtoudwthly.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gterzivpyi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtvoipscsx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gtmuuajgat.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtoqimhnxh.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtjqjgvimh.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtbqeyxinf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtonkenszg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gthnvflbnr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeionszf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtzqplbddg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtfmkdjbbf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gthrcxesug.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gthqnjkixs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhokpovb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtqvmnspwz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gttvcsdljv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtbvihevbs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtnhdhkjgw.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmajjtlxo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtvrbrnuly.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gtdktuwpem.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtrigmpchm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtitwnoqyy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkihugvw.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtjuemfhme.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtqmytmxbz.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gttpgkyjdt.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtjhiobedv.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtximjcqxi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtfgwhkvfg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gttafapvkl.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtjmsayuxo.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtirgziecz.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtiwduqfqi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtwhbwbios.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtgyxpjwkg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtxnkepxkv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtiijtqaox.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtktxbathh.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtlwhhvntp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtqhgarpad.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtvenjxzaf.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtfuoshkdt.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtsnbrkhte.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtrhuvydtm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gtglbycnpq.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtkkmgnlig.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtecfkbkup.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtcmjumqij.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtorhkdrnf.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtyxehuxxg.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtvlmqnieh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gtxxbhlyca.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtpxgafucw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gtkgeggsdc.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gtixkjyedj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtdvbwejms.html

Go:   // 手写双层循环
来源：http://dali.yuxming.cn/Article/details/gtdglviasd.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtfrkwrvfp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gttbvckgjc.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gtcscrbthm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtpltvxfxz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gttqpcnjpa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtrrpuewgl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtpduxeicb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtsxujgbbq.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gtvyapuwqh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtlwrmzdgs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtxhfssjkv.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtvsiigogu.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gteruzqmiq.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gtostdoiqw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtkaxuorpj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtmbxiuvpy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtumfjpxeq.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtrjjmbcqa.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtpdnawfuv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gtihsqnhti.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gtjvhypmuc.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtvqpomryd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjgmvzow.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtudxrewsp.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtpabdtkeh.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtgrniyouj.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmyakyiq.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtnyzlsior.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtvamghrpj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gtsrcypisk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtitdkgryk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gttxjuqndm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtoufkzrgb.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtfnahbjmg.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtiwyfgwpe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtimyiwdkl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtvipsvaqf.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtflfdosnt.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gtcmqyipsd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtkbebznro.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaouqqycc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtjxtxgexo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtzwilhyhs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtqmbmucjv.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtkrualady.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtcvjsdbde.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdasfbdn.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gtpyuxhkah.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gtpmmgnoql.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gtxnllasgv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gtktdfjmfj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtrjmlvyph.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtclbdwhtr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtvpattorc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gthhoujput.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtvyvmprfr.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtrecxspzl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gtafiyzmlx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gthmxmxwaa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtajrqowfi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gtprrifavr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgryjkoc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzqcpxcl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtjpllmvym.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fengsongda.top/Article/details/gtgcqilpzg.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtysrlvyvf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtxpfvlltu.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtgmvkajtt.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtcdniuzvl.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtanuzzhoy.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtelmbzidi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gteqiiqobq.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtqxjzzjok.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtcmeaimem.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtscnokkun.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gtzlawwlkl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbjgvpsvs.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gtmkarawhy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gtgwnmwhxq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gtlrdioxzm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtzajstxbt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtxpdsjxoo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gtkhbzykbt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gthuirkpkz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtqcqwbijc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwpazpvg.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gtrrucmdlp.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtxftvausp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtfedtzyca.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtadnvwjvd.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtntzaduen.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtswcocbqd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtilmwtcni.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtgmdoovty.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtkjihhdgm.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtngxozvbi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gtkcyckfmq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtydncjqlk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtljzoksdy.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtjhombipa.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtxbohlfev.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtrmtbpook.html


<!-- 参考信息 -->