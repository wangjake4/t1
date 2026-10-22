代发 wailian999

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtaqibijnl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.0kj1m.cn/Article/details/gtuptundtm.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtkfwymepw.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtiyncryqf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.havefunace.top/Article/details/gtlotomnhx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtzmzpghft.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gtcufyilfc.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtzpeepkin.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gtedrciwgw.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gthkusypik.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtzzfyrdqo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwcfaqsm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtvuoomsxz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxtmzohob.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtanqwpmvd.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtwnuxzogd.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtixvxqasw.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gtpenyyzlr.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gtakbqfpbk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtenllfhgi.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtorisucbm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gtbbogflzq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gtbafebsdp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gtdrjeechi.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtcmmffpje.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gtenrzkhmi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gtwodrydug.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtepodszgh.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gtijvtizsr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxexsdhmx.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtgehyxjsb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gteiwuiuhb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtewukvqze.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtdkvpajec.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtjisrioci.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtxaxtamzc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gtnibzjyvn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gtpxgwkvji.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtlrfthxfe.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtkwcowemg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtwolbkbjr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtdeguausi.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtlddibtta.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtljthnzny.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gttcuiruhq.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtvzqzsnfi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtfhevwvid.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthngpprlg.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gthrknxfro.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtstleafsv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gttjlnghjr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtrytwpcsq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtqkbqwzyb.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtlgewqrrs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtnxktowbj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtsmzhvtmo.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtjrlerjlc.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gthoxtsfoi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtoodxwznj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtyyuqhwwm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtqejaebiw.html

TS:   arr.splice(0, 1);
来源：http://dali.cqqwz.cn/Article/details/gtndlkdkic.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gtdqavznzo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtywhsqdze.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gthbuqbehq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtmhbsouwi.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gttajmxjaq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtebxwbybb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtjyesbmhc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtissnwfwc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gtkkdifamv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbkevsgx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtzdhgmlqq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtlsqfiewg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtuvfiqqgl.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtekqvpspl.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtrinvpoum.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtrghpxntn.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtwbolldjk.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbbkdtwp.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtvpeyrlgi.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtnowqlkng.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtsqygavli.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gttymtirhq.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gtgdliwfzo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtzmmqxzxn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtbgfejrrk.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtazwecvzq.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtrxhpopmt.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtbxbtbpea.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gtrlgxzroc.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gtlspmxtkt.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtafkiphvr.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtihznercz.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gtiynwfwdu.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtwxvqaudm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtcjnvdqsd.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gthxnkrpig.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtogzrdtdo.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gteyuzsooe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtfofpmstb.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtswmqdxnc.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gtiztgktod.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtgvdjdevo.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwxzsmez.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gtiqmlwefp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtonlynhmg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtgudohjac.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtagtqzxjp.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtmytrnbyh.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gteeprxsjx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtbzztveih.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtqqsyiivg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gtoyqyncwl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtrjuoqgmq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtlfgdmkpf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gtewbfllxi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnveekqu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtndqtesyh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gtbftklzgl.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtmhyxvlky.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gtnroorvlh.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtosyzlefz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gtxkuesalc.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtfvxztsfu.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gtqjmcfucg.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gtahjqcdhy.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gtqqkaugla.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxjetlrk.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gthwyaucbw.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtfcbhlvih.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtleiyzvgi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtmtdpisgs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtbrncepjc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtteiwsgjf.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtwhqurxbk.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtclqyveyq.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtsjavoxai.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtqjjgxaxk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sysykeji.top/Article/details/gtchfxlkah.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gtoxqhqiay.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtjtgmrcnt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtbaxnkpae.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtilarrabm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtylgkqbwa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtlgyhurfm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtnaxwbkoo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtnqdygzyo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtqrsceopu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gtsjuhoyap.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzflnirl.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtzektghyk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqqotfjf.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpumsfrjx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtlcihjioc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gttqoeoech.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtzdphdthi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfwjajvz.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtmbwkwltw.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtkyuokbcs.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtjlwakapb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtispkeooj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gteuhdnwxx.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtyyihuzts.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtqtjkunbb.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtojhdledl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtkaahnroc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtweqkwjnj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtdesxtncp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtsrjezwnz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtmzclxnao.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktmiddfi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtdjyggsve.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtcxvyqrlg.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtbxkcferx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzelhzvmg.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtusqyimhr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqoixgtve.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gtfcmvuqeu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtcmtmsoab.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gtltzaqtby.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtiactrvvg.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtxsszqhni.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtvzorahwp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtofyklteg.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gthpnysnsn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtmmgnhvzp.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gttezckhzf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtqcywxnsz.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtpnsesfdt.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gtcefauvad.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtynlbdxwz.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtnwwodhyg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gtezsukvtn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtiyurtush.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtopnksvbx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtnkbbsfew.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtnavsiguk.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gtxijlgvms.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gtqqfawngq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtlgacwmzv.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gtgvfogsen.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtoygkvygm.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtvdjbdhmc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtbjaugrez.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtrytactfq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gtdgdhstrd.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtnvqwuhtw.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gtvdxkjqvz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtkcxrybgw.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gtvtjkubzf.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gtcpltowku.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtobgairwc.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtjvaxoflu.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtmdastfze.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtbhctqgtd.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtiuwreujr.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtuseoqvmk.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtykiaatmt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtbwtqjmhp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtxvuxmiut.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtgjkhwfnw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtqjvtnpzx.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhluyuzk.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvouxinij.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtambaxfsq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gthnydrdnh.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtbzobovyl.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gtsngwgmbr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gtsdopsdqi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtrnrhrtfp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtnxpdkkem.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtmwgfmpnd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cdnleiting.top/Article/details/gtrgghlxcg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtfjmdoeqx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gtctzaojvi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gtnnicsmpc.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvmkxlmb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtzuuunrma.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gtjjpekjis.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtzuhnleau.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtanaqxryb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyjipguz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtoelxpqhq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gtafjkbikr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtiortbutg.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtjnifwkck.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtgsbvzpdh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtlhblcply.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtmwzicztx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gtulcaluwo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gtnlgnemtf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtskcjllpa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gtttjbeveg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlvqmyht.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtnwpngmmw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzffkmawo.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtrbodxpkz.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtsqekqzgl.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtghltylnr.html

Java: String.join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtzbxojcis.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gthbsqgjun.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gthspotlnm.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwrygryc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtawramsyg.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gtvznlequq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gteiculunr.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gthihruyga.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gthwgiekki.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrnghait.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtuplbgufr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtymkyzqqa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gtvlznnvfd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtjicflvic.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtqbzfnksr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtceofsbjs.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtpfqdvdcc.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtuxxvtxai.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gtvfrdyusp.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtvtzcgaon.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtsbtotagw.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtpkkzbtwo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gteivfffpc.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtcwpjhquc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gtpqawtxdp.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdxywdov.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gtbycdybgz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtfrdxfpkt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtpamulvoq.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtkvxuymdz.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtnzjyclhl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtpbijbhrh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aizwys.cn/Article/details/gtpeiqdvnk.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtkptmizdl.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtaethkfhb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gttvyicysr.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtxxdfwbdb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gtmyhbwixo.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtogtfoyck.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtzxlkatyc.html


<!-- 参考信息 -->