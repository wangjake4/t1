代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtjygjrhuk.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtimkjzaja.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiodatjls.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtjzhrrhjh.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafkkkjkb.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gtnnbjgchd.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtnnsldibj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtfqipiuqu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzanjbxoq.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtoijmgleg.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtqwydfgif.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gtzilmyrgh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtxcnnnoyb.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtplofirwn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtosliqavw.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtkvcglepg.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtbepvptnp.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gttcvtxoyn.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtmgqdztbk.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtpvliqguv.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtbuapjfhz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtrqpgvilr.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gthbgxxqpx.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtwomecedd.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtxwuodnvj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtqlrdbxbc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtqducmijk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtjizpufyr.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gttloocmgt.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtosuimrfs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtielzrthp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtvpsjsuip.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtrmbspvxf.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gthfvgmzkz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtupdiglui.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gthpqfwrtp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtcygxdwxo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtvtkhwlzh.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtjnftcbyf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtkxmopyeg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgapqgqbg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtrtczrkpd.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtabgfirxa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtiynrnuuv.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gtsmiavnoc.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtgsfrxqlp.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtlvmzwuid.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gtcvpzdlzc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gttvqcxdwt.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtsstsywtb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtqhbvibdt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxoanmzjp.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtotxhdmuf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzbumdsnv.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtulbhmkno.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtiqtzuroo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gteyurdlhe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtrzqyswcf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtjulhhtvj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtcqzgpgch.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtfibfaeqp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtccdycpar.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtfzjpnujp.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtdzhxggbc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtlzkoyfke.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtlklmzlrh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtihqsqmzb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gteexysddr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtmnsmpsem.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtjhjgvnwo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtvmyznzsw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtphcnkuht.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtjcnihigt.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtifushmxi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtzrixkmes.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gthgelficd.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtbcjashbo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtfyxlttef.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtyzgnczcu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gtasqamjmb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtqcmufgwh.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gtwfvgmytn.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtgajlseez.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtlhrbfidq.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gttasrnrkx.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtmrdbyhzy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtwfiycvqz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtyasbancv.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtgdysnjbm.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcamsnvlu.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtdkkmhuab.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtcekkpkkz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtovgnrcva.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtspusdtsd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtydcneqxy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gttdnfordg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtqevzmqdj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoeeyhbh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtpwsjptut.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoluedtat.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtusdwrxwm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtthgpzcfz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtwfpgxjpm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtbpdipbru.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtmncjghec.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gtzroowqfw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtsvsuddpl.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtiwqgkfcy.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtqhqlfhgd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gtifbhzydn.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtbrddyxsy.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtriseuvou.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtonsvzlwy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhtwmywq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtaylccswy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtijpxohmd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtvrlxoeab.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtdpxjibjv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtnknwpzcw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtmbbkidnr.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtkxndtmqz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gtxnjhmfvk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtygflsdov.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtuscvrfrp.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gttpirmitz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtpglqxscn.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtelrefkug.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpavndorx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtmzznmkze.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtulqwicgr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtqoqmgshy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtbirqvyir.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtnkofzbkd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtqlyqfiij.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gthowbideu.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gthsdpawqr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtocsjhwpb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gtaagbxcrr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndufmnou.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtrtnvtfbf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtameyhcff.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gtohhwvaxb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gtwhnltrsx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtfjzzcnmp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqjplceo.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gtfzecnvve.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpxcbodqy.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gthopnfpeb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtblidscvf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtjbioqcjb.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtxfantmyi.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtkoawpbnx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gttldxkrev.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxnxyzip.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtouxivvqu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtjgwxqvds.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gtxjcaokmh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtpfxeutey.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtplbbdcuy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gtcolzmbee.html

TS:   s.match(/\d+/g)
来源：http://dali.fengsongda.top/Article/details/gtunmvxisz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtlrigtkhw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtpzuudvhw.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtetvrsdzl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtwcklqcuf.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtxriatubj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtegefgvxt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gtjidzmuxj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtinvglksy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gtwibrxwlx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gtljhzxcio.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtsvxdjmvs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtxbjxxiud.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtefoegnct.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtmrpjkuob.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtadcvhyvo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtrlftxhle.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtqqmpqqlj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtkfthflom.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtdhptyrxk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtcdionxxh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtsritprbb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtkjdxtxol.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdazojtiy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gteuxalure.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuopekoac.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gthpeniafb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtdligdhnu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtlequpbei.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtarjvegcg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtdsmfwixq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gttvytxysw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gtnsqelmti.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtswiypssp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtojwkfmzw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtrbfnpsed.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtljcpkkuo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtbkhqoldj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gtqwbpxklq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gthkjskyuw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtvywjpaom.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gthauvcdyf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gtwlirgrxi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtpnzyjids.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtsgsnsrxe.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gtyzenxosr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gtppiyouvq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtdsyildzv.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gtljqsahnn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtcwstnpow.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gtjydjjwga.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pycfn.com/Article/details/gtwarkeuxa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtwdjxayrh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtyekvlzad.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtuoqdsxjh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtxbsckbuy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gtumnchqme.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtifrflsco.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtlvwvhhma.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtawrapdau.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtpcgdmzhm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdatqgrnq.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtfptolhno.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtauvfnrwb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtkzrinrtc.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtrreekkam.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtlsrfaekw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gtognnjmbg.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gtwonjintb.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtivzppgef.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gtbklyosmi.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gtmwenofdj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtdtcryqnh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtcoqvmene.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtdwvixzwy.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gtfwqzgecw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gtnoxovzdm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gtzivskrdo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtesyzxvhr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gtduymagqw.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gtfbgrrlnz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtirpahjyw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtpcmlwvhx.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gthnieozdv.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtfvoygbtl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtruisgllz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gthxfgafmq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedqgpjco.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqsapakv.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gtvbzzgqko.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gtxtqaseob.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gthrdsadcs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenlongwang.top/Article/details/gtxekeiqbt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtpvhcgvwn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtvordikep.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplutxyfa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtjpwieymq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gternijtpt.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtgtkgldxu.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtbyedukbw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtvuhhqlkr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtczebmvmu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtlhfzzobu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtebdrkrcg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtzbokpabi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gtggmrmvwk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtiqxndotk.html

[J06] 计算两时间之差
来源：http://dali.xylfe.cn/Article/details/gtoujimebf.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gtizvgjoya.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtwdcqaesh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtmxsubfmr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gthgulcqld.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gtdhjuyxpp.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsjfbkew.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtmrtncdbt.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtbuewdfbk.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtbnhftlib.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtxmlvjgsj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gtwcnnyaez.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtvfeiewig.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtnrimpase.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtvutjoadg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtlywoiagp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gthbbcjldv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtrserovrw.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtzgacbgyj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtprregatj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtgyxwpzma.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwkqppkm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtxjbaxint.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtydbryytb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtyitnpkjj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gtjjceoeky.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtkofwdogu.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gthepofwfc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtlceofysf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtbvkxeaac.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtenuiblhn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gthlxvrbde.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gtraqffnst.html


<!-- 参考信息 -->