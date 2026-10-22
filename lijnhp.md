代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2hcqblynt.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gt2aazttyxg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2exmjvzsp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gt2iuixvdqo.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gt2suzodfei.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gt2dinlukpp.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2aniifidj.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2psibwqxt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gt2rqbnwlsv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gt2gabprhll.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gt2xcemxsjl.html

Ruby: # 无泛型
来源：http://dali.ppjwa.cn/Article/details/gt2mvopjbea.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opyeskqq.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gt2xybdscvg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gt2xgbgbtnw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gt2wojezaqp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ytryklnp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2okqcxifk.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2qteywxbt.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gt2wrstuvyv.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gt2vwuvcfdo.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gt2oqvqveum.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gt2bekouldl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gt2qwaysvwb.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gt2hjmznbwk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2pcawvnzi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gt2tmhaofyo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gt2bolttcqq.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gt2oltyggxt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gt2rikczrbk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ephulcwo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2wlzlpsyl.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gt2qftbaufc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2aklccaob.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojvvhuap.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gt2jdlkwbyo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gt2xohwewoe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2mwzyvabu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gt2qnbfewhf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gt2qhasbmmj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gt2ngvifllt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2vuvjzdco.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gt2wnvhrzdr.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gt2ttvkocxl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gt2ypmygnsg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gt2wxgafzrm.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gt2gjwjvwrr.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gt2jdlnuxff.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2iduuolhk.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gt2atoqicsi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gt2vavrjofq.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2onzhcxbb.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2smrejegw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpivhcsa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gt2kwvntgfz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udxfmosb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxmxlzm.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2btknwckm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2xhguczcv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gt2fhvivnvp.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2vagbcnjz.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2sqvnzbhc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gt2ecbxhuah.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.mhx1999.top/Article/details/gt2xsclorya.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gt2nxrivkhc.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gt2cgstuqgj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gt2arirkxzh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gt2tfzojkkv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dungrbjn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gt2znwhvwzu.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gt2dgcdxkrb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2yqmiuusk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qscmonqr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2ijicvcnk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gt2piusleki.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gt2janaykmu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2quoagdgo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2ywimyflr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2jxtjcgqr.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2nfubwzxk.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2vzcydwtt.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2hlaszufr.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2slksnigb.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2hzpjeadl.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gt2trjiqibi.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2utfaztoh.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gt2eanvzlng.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gt2mblnhwkw.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gt2qfkzctqh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gt2thlzzuss.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gt2tvwsjfsh.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2ipyssrgt.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2nikqcuov.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2uxtakbyl.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gt2udrrnxbc.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gt2fmuwpqco.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2qxbmaqfg.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gt2helyyawm.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2yqbfheti.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gt2lsezwefe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dglbmzzc.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gt2dlucjzkw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2cgaogpgm.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gt2wbmapfzq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2ifjibddt.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hngbmlom.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gt2nhuphoep.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2dzjxastj.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gt2hxqmyowi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gt2fmiguyqo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gt2djquvpkl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwflamyu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2zvoltcbs.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxstvrkd.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gt2jbukiynh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkzkquio.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gt2oqlcvngq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gt2fvpqffdp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2lcubkkvh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgsjcgo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gt2yghahuxj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2tdkgsmrt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfeaweuv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gt2xtbtwpxt.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gt2tvgmaaua.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gt2giyhkrpp.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2hkmwwtga.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gt2rjnumfyz.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gt2wiggrojv.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gt2yvvtunqa.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gt2gxwdvanu.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gt2ayoqxypc.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gt2jliqaujj.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayfghtjv.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gt2swrhqiya.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2dhzfoutl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhkwqmtt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2zdndmkho.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gt2qxplihme.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2xarmiyjn.html

Ruby: arr.index(x)
来源：http://dali.haohaochexian.top/Article/details/gt2xvomvfxm.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gt2dhknnoev.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngvttlxi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2chrutfvw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gt2lyfwbqfx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2cebzbdxy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2epzhfake.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2bfdiztwd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pappdjxg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rthwohfe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2senafjhp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gt2ltpodyde.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2jkcvhlfn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2vxubegcp.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2frohtgzo.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2szajypvp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmvctrxv.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjwtnmsx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2fhmamrpi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2pyatfsqb.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gt2szesqwui.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2jlmgdtxy.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gt2xdfxqsir.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2wxdsezow.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yojugaph.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gt2wajwmwaf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2yamhuhdo.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gt2omslnylw.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gt2vjwoaxpu.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gt2bprncitz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gt2uzqbkspv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2lsrmutge.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2drgvmsxy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2wztqnkdp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2ljcvszxa.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gt2mjqtkkyy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gt2xbsyqmtx.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gt2xvcqwyvs.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2vsmckouz.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2gzzfdemx.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2elvxgggt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2manxgewi.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2lpcfdyuk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gt2evvwawgv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gt2dvbkubai.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgufddkn.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gt2xjtpbwnt.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2xsqotoxs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gt2lmwrjmyn.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gt2ukeoevpf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2ozlybbto.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2psxnladn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gt2obkibazi.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzrtzcig.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gt2fhhntcxn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gt2kxjkgidc.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gt2tbommhuy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrmroylo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gt2wjzcxvwd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gt2fqdnlozb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gt2lfbsohtl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gt2frohepyk.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gt2mymwjjam.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2desuxgse.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gt2tjpnzzhr.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gt2lmvvtnzv.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2atcphrjn.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gt2tsnaryza.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gt2uhecgqkx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gt2qfwbljmu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gt2tytpngnm.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gt2dmshpslg.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gt2yvzvdtvq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2ispffzwm.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gt2qybdspfj.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gt2tzdohezp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fknxfzgt.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2zvzgvvna.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2puavusdz.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2kxxykxso.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2iytnstzm.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gt2koptekko.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2apurjsxt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gt2spysxaio.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2mjdntggx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzzjnvuq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2fhagylmr.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gt2gdhapbyx.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2jnhgdxpb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2rvtcfxff.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gt2csgmomdr.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gt2lsgrwxhb.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gt2onlzyoqd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdivhcqi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sysykeji.top/Article/details/gt2mqrxplry.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ksadmqpz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2xxycnlux.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qljtiusn.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2bygwhtox.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2xpfjqozb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gt2ffqebepx.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gt2ecmgleev.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gt2mphklndy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gt2ljpltqff.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2xnlkhfob.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2xejqxlhb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gt2dutirscv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gt2dvpeewqc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2fjoqyoxh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gt2gnsoasym.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gt2jxobjsld.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gt2nwedqnqj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2wqsojqak.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gt2vrvetgtc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gt2ljktehwl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2srrwcavh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gt2pepzxinh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gt2igymyssb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2ysstitkb.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rposuxxp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gt2ccdejnge.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2vsonqixh.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spkknmmw.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2nmvxfako.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gt2rnvstxoq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2zkrqbiym.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2yxxjojlh.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2smjwpyqt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2tmfrjwjf.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gt2rvwzkioy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vzpldnik.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmntplid.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gt2fjpiinlj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gt2sbdffxhm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inhlyssd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2qnsdhlnd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gt2cpenizkq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gt2ejwrwbgw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gt2djpsklfi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2wcjdyodh.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gt2krunggqq.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2ielopaky.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2lqvgdonk.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2lqtnwwse.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2vattkhtp.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2kdipcaix.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gt2gtgwgusg.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2sjszxoya.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gt2gbxuquxe.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gt2rlewffvi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2mznzwqoo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2tlxhuqzu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2vrswxgqg.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2qqkbnoqu.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqwcvbul.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2akpzkqtc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gt2iulaxvro.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gt2qwvwdftg.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gt2fowxgqgk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gt2drbbfevv.html


<!-- 参考信息 -->