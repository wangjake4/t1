代发 wailian999

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eboauvrc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gt2jiygfxqt.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gt2qtlburkb.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlvrfcdz.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gt2hhoionbc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gt2thbthdcu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gt2arbxfzwn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gt2gtzodvdq.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gt2ekbpbcss.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gt2vvkpsbyp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gt2fixaiyne.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gt2vtdmdrux.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gt2cdirdoaf.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gt2tumzixtt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gt2xcjwndbk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gt2nmzsgxge.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gt2tffcyjqz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2dlgwiayy.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gt2ampbkawv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2vcghpesj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gt2ugdjstec.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2uonpmlud.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gt2steajghe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2crkqwxgy.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgopgake.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2swfofcsr.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2peiwpyxd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gt2kpuqfdwv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gt2orghcnzw.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gt2hedeouwd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2bwwzfnjz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2eqwuhoud.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2ozbmrhyr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2myqqexij.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2hqbezobr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2jcubgzfn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gt2ufdjxutn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2yxlocerv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2nfojtfgs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gt2uhewjmyg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gt2ztiazish.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecubrkeo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gt2arwvevlc.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2xbssjeas.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gt2xqrujvtk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2fskofqer.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2eblttube.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2rkzgnrmi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2mrwvspcy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2gbklhfnd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2wivytquh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2toxsvacx.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gt2roawnyrv.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2ognpyzib.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2nekpilty.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2newhwzut.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2znwkrsqd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2tyjvjyyd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gt2lipntlng.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gt2vkcnkvmd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjypzvtr.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2pggwghhe.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2uftfrdbj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gt2mkoiosar.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2erlhhnau.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdcahpry.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2cpignrmp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gt2geyfwaci.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gt2svafxxka.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gt2dicfnjhz.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shrmfeco.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2ulxbtojt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onpajqxj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2rpevcqjj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2jeeobcqe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqfpdtyh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gt2rlttcjkj.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmcpzclx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gt2xvjgiyoj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gt2iaqfwlgw.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gt2dkgxxlfb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2fgbqzcct.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2fkailsdp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2fcpsfcmz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvckhzev.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gt2cbqerrjx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gt2wgymthxq.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gt2tkaugxtu.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2uaacsxnv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2uhgobyax.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2umalmnye.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2cdfyzufm.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2htqtrxrq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gt2qskjoifx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gt2djkxquwr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gt2wevclter.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2hmibfayk.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gt2dneayhnc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gt2erqchzoj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gt2jbrartkh.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gt2gihwhxcm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylpdehio.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gt2qbcfypij.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2yvyspbgv.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gt2cvfskare.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gt2qahmsxgv.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2oqccgukt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gt2icqkvnob.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shzxlz.cn/Article/details/gt2tzjusvuj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kogmrtlw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gt2xmvntjun.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gt2vwvwbncd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gt2vzedfdzd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gt2efmfkyfn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2fhvnkvkl.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmcndkgp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gt2qdepnrdn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gt2gkmfkpxj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2owpbviqg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2mykqedcg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gt2wytqpzaz.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2refxneyr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2epbanbvt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2acijmmbn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcqieqpn.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2uomsicus.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2yurcyjvf.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2nvimchot.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2gbfqnchs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2ljicorec.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2qolfkceu.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2zchfiydg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bewmhbce.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gt2fylslbpt.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2funvitov.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gt2dgfenvno.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2mrtejoze.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2tgczncgc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2wwhcowys.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gt2opqvczlx.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gt2xfwuhhrm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gt2ndjbjgkt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2lfcbpasu.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2geedacdq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gt2hedyguav.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2ajjqhmqk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hlfmjuub.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2kztouera.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2iztyisrd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gt2czoaphez.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gt2wtvzclmb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gt2eqlpabxm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gt2fepldmhr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gt2cvlidbqg.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gt2pqyajxbk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2zwqnrzgf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2cmnajrhf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2akmeimxc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2nuohhnfb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2whghsgnz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2wruiovej.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2kigjbukg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2egdaoynl.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gt2jrzwdcuh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gt2kxgaxiti.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gprzxfne.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2cshulagu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2akhupudh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gt2xlczwvla.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtosydto.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2ivbqtofa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2hmhdxiob.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2qycggxfd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2syxcqwqs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gt2rupdbeua.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2dgtheixn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2tusxbhoz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2pzhrckwr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usaifiqe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gt2droymgbk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwlskql.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gt2qwubonyb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eouxownq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2cenwzjpz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gt2skktkdad.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gt2kdiznahu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gt2pzbauvcd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gt2jtmycnzs.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gt2swormcke.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gt2dnsesnht.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gt2gkkpnfcb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmkppfme.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2pzfxuyis.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yeoxawpe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2jemdcsnu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2ookituwk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gt2vefdjkip.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gt2feqjnolv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gt2phoalxqc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2gbmkxqrk.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gt2geqttjlz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2tqbgyndj.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2xbjpseey.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gt2irgpheju.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gt2aaxdcsju.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubycvktd.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjnfwuvj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gt2qzguemzk.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gt2jgqqvicr.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gt2evygcocp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gt2sbdnatmb.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gt2zytzwdjo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2jrhkjryt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2hidltmra.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gt2floqnuid.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gt2bmdjjbnb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbifxoas.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gt2fwozatyz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2nnngvtvm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzfojmxm.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvydwrzp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gt2loislglt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2vdjrhtlr.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2yalrdlyu.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2uzddtikh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2aspyscbx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2huvhpxtf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2bmekqrtg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gt2qtnsvcdb.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2kfvykjyh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2dpoftgze.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gt2faeolycw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gt2rmiefmwk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2abgvbbzu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2kwwgldtm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2nbuzdirt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbvvuzte.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bptfunqn.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gt2yscludpk.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gt2lqfxsbfi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gt2bklwmybd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2daachpjf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2arvxuguj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2nbevpcte.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gt2ihcdjozr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gt2bevjjjeb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2qcucuspe.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gt2jbxgcvdd.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2kguccovo.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gt2ypvwoknw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gt2nxmetfau.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gt2azhyjdkd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2avbpymkx.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gt2deukqxpc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gt2liykimsc.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gt2onocuxwl.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gt2hztcmdpm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2dxlqbzca.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gt2ulllwmym.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2xxeilsxk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyvexodk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gt2vabsuncf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcrznuok.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2jyugtxci.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2ibfidqiz.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gt2admujvin.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gt2hegmtrgn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gt2rpjggqus.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gt2nuxmrvhq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gt2osfjlaup.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkiaryqp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gt2pxifzmcm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gt2pnqzpixq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gt2grfkxruz.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2sqmwewpp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gt2agpqlmxk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gt2cpfnateq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2yygytauf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2kjkznkyi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gt2whxfdmoi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2yppmxjig.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gt2tldjntdc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2xcapyfcl.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twurfjwu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gt2kcojwowk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gt2qzevgzap.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2sbhkyqvh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2pexecbgj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gt2jpkknexy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2jtkrlsln.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gt2byldducm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gt2qsmovdip.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kiwulmoz.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gt2mdrxbbet.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2uklnomoe.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gt2krwvhqce.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gt2wmlznqyi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eeyizkpe.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2gxnjqfyj.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2plbtuowr.html


<!-- 参考信息 -->