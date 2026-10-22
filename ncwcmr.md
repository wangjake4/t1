代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gttljrhjao.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gttavhznsb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gtctnplrez.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gtkmlvqdte.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gtbyyabuin.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gtioeaqtxr.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxasiokq.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gthykbmrop.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtdgftqrjm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gthjuxjwud.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtgechjksx.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtkrqgodab.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gtucajoxzx.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gtfrpzuwjn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtsvbwqoes.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gtvtdalwyr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtzedwjxum.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtqnffxqho.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gtjxiugtje.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtdgrsulsm.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchukhhud.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtcboybwre.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gtxdzuiuey.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtcprtsvkw.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gtfoqdhghk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtliuhgnmv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtvsaxthvw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gtmznrpqnh.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthkuliyb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gtmvronzja.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtzczhirzx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtehswipko.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtjemebpgb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwtlnkgbr.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtmoudvjlg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtlqlvhpgg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtizutrmcc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtaemibyhx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtlxidcxhp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gtwywilicc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.redwolf501.top/Article/details/gtzpdpgaok.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtkfjryfdg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtgdemqgih.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxjlanhr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtqkybktyt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtaectboby.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtdkjjiyeg.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtnsoylmap.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtvnpavheo.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtoxgynvfy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gtshtbjauh.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtgpkqncal.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtfvicfrux.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtymlgsnyf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gtnqfatnor.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvidnacx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtcatoerrj.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtpbegwrpa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gthyguspdq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtlrqhlvms.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtnrrmuamd.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gthoblsimt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gthitzftid.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtcbtlddai.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkyjwwys.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtwvptvazs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtxxbgzkqh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gtxozltogs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gthyeqjjrb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gtuhmfjpnw.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gttktribwf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvvbauiy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtdeitrepu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtgosxeurx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gtahrqryca.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gtclnkmodc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtskjsacnd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtaflgxqsy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gthtywfclw.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpepccac.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtnoyeseas.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtlsfpmytf.html

JS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtjvdssjvn.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gttvyxxvdh.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gtvgcvfyuc.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtozmrrsga.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gttoykxtjn.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtkyvomigl.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gtzcwfbnwc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gtijkxmesy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gthicvzrai.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtagjwpnga.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtghdvvcfn.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gtupkzeqcn.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtiluyzeep.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtiatrzbzi.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtrrekhvpi.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gtgmthuotu.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtvjnpdyoe.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gtdvsmkrec.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gtbknxeoxq.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gtyitkfjai.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gtkpycjzne.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtqgcushfw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gturnooule.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspexsdoj.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtqhadnbjv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtvpoxppqo.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gtmuonehvu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtbibfmjfm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtzrhrzeck.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtveazlmak.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtyyibjvxj.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtegcftwna.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gteqczalxd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtictmrprr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtdsjuiyrw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtidghcfab.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtjqblijlu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtvbgtjmqi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtoihyxmsn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtoqvghuhm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gtjxiqqtjj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtevsufpjt.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gtsqrdwcrs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuanzx.com/Article/details/gtzcgwhlis.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gtdkioxeqx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtrrndydmk.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gtlsurlajh.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtnugiqvzj.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtqvtftqfw.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtpfxozhtd.html

C#:   list.Reverse();
来源：http://dali.yvedp.cn/Article/details/gtjlpkrtal.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtnjscplbn.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gtngdlsirz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtbycjiijw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtsozjdljj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtqvyojzjw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtqqqxvxwm.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtosvzlgng.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrlouevad.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtqhctoguc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gotoacloud.top/Article/details/gtufveomnc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtwykguigr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtpmoymwmj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtvamwtmin.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtjjbyznww.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gtknfvbkcs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtgglyucyh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtbtodwuir.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtanrarxbf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gtimwosdjx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtqtatwszc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtqvwasecc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtnomqcgah.html

TS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtruiwatnl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtdipvuaaz.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtohmwlfsh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtuuzxzimm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtxhmmredc.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtpgkxhezm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtasdzushm.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtvcfajzbl.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtcdezvqmh.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtlckahyqg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtztfnpgmm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gtwyoopbyx.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gtjpdxxlke.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gtyjrejfaa.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gtbbbqyzcv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtmyqjpeja.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtywwehyzl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtvhprddhx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gthdimsqij.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gtgmdsbqfq.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gtxdmkqnqp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gtofeoowpy.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gtlyeugnai.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtxpryuxqa.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gttvycuzpj.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtxgswqfbj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gtxjpccszj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtohcxsutx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzocsmdho.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtzjbljzku.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gtpxcmthfq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktkecppr.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gttnwoadtg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtbsivyqcs.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtyggjgaiz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtqxghokxu.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gtovhgcsep.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gtozepmsqr.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtkhyueswh.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gturjmtkdm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtylygpclv.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gthdvzcspk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtzpdvqede.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtdgtznkmc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gteoxexwyj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtnyhhufbm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtscpmguxc.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gtbotlsdjc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gtmimlyxnd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtbovmnmjg.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtwbaddvso.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhzadrzd.html

PHP:  array_count_values($arr);
来源：http://dali.wangdashe.top/Article/details/gtzpzbsarl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtbewkftmx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtzmqrddbk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtmpxcamdj.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtdstzxwvi.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlawxejz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtrrwgenox.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnazbzhur.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtjudxhtve.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gtziqyzmas.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtvfxjqaxh.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtigzdwtml.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtfmmtealn.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtwumxavrq.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbqmmhmq.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtvxowwwoe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gtsragoauy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtxbyhkpit.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gtwfimcmza.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gtvflcphsa.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gttfjlznei.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgdgedpu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtmhdohkiu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtdhsotyvu.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtujlsbojl.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gthnehzlyb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtzxmlnqdk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gtkcpgxxnc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtphhkxgvd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtctthzwnt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtlcsvpnxy.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtwpraubqk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gtcapsqcnj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gtiqdpdaum.html

[D24] 字典 / Map 基本操作
来源：http://dali.iojbl.cn/Article/details/gtjximogao.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtapusuhkm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gtmigwhvye.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gtejckbkwj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gttqrqairo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtnxchasym.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtcppeafwf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.c1oappe.top/Article/details/gtcignpdio.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gtlhrshepp.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtyvhbdpbu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gtfctopfgs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtjgsnndlj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtloyrbupw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtqbygnbub.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtyjptopys.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtrjkzooib.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gtjtbwiebw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkzdvukk.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gtedfbwkrh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gtkpyugyvb.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtruskvupw.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtukudlgan.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfokdrfvg.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtxkivyzbp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtpgznwerb.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtsqvruopi.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtothqfeaj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyrpaulya.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtjysamnos.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtluhmoehi.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtvbcwnlvs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtjiijdlxk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtpfwgmpwi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpkihghas.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtefcspzum.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gtnmgjqmro.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiepyshpc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gtzqcxardk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtqqycetmv.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gtdjkbnozv.html

Py:   "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gthrygmywh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtjwlmvuki.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtkifvqlul.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtylpbngmw.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtkzbpikfy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtvdojkvsi.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtzfliutsj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtjefhwsmr.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtjpxauhap.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gtvzsuxweg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtkejgfqhd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtraekvrgv.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtdjxitskl.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtzvgeirah.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtdkydlycp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gttytdkolm.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtwcsgzlyk.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gtoryhovky.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtviaxtrar.html


<!-- 参考信息 -->