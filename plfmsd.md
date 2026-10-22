代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtubpyrgsc.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtioxanbjc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlotofdus.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtiztsxlok.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtkwprrcdf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtfcmemjqj.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtwagslyap.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gttdqhdytu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtfabhffkd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtkalcyjjj.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtvvcwayyq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtcwusrtgp.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gteqzwpqep.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtxjptyfkd.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtkctcyqmg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtyucvazvy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtbvgiuehj.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtqvniqoac.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtqnmurwtj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtoliawknf.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtgtfipjjn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjjgorkwh.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtbgnmeiao.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtkggggjum.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzshafxnf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtlnpsimzm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtaioghjck.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtuysiryit.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gtiymnqzzt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtdfqefhqg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlmlhzyy.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtuabzrjdj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtrdikxvnb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtvqbnjjhh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkxsgtbx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtlkijnaqf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtfnnwxhpr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtudwbouhh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtsxbrkstk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtimjwhvts.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gtwgxuyhne.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtdbxrfbax.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gttfslrihy.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtwltosxjx.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtjvhurbum.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtbbmiqsyy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtcopticnn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtskigqygq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtnmnmkrxy.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gthyrrgtbd.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtpdbvjozm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxxxdhzf.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtamxukayp.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtekprljto.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtbicjwrob.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtzuqzglxc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gtuewsxfls.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gtolkdbhlp.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gtbprelnpy.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtcwrqgcti.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gtsultdbio.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtbqlwsboe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtptqnweer.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtxkuovlzc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtfsiivgtw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtwkmwsoii.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtguuyhulk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gterkzrxtq.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gtzyhovxvl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtdizijfll.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvdqgurf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtkkilwqjs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gtaabiycyh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtmtklxvoz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtulzwmcrx.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtrkoqieer.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtcrlakzex.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtonyhyqbt.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtnqmpmjbo.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtxeexzzia.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtuzrsmrrd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gtdcebhxmr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gtzemxpzhn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtgvvylwum.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtdetxevfe.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtdazbfnkm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzivaszp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtfpdulctm.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gttmnoykyk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtjsvudzil.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gtsdaieuxu.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtbcrlcdvf.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtrnagsiao.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtltnjbzru.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gttgsqzorw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtjlcsssdg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gttqrjnioi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtyneegggd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtlokjzjzw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gtlevywann.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrsoylur.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtecryknlz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gtooogoldh.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gthdezgaar.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gtxsyitdtz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gttlgmqcfb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gthmnsienv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtgtrinpwo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gtpuuuwjdv.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gtgznqbbnc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtervdkenf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtpqyvttsw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsslwwbps.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtqpyugsoi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkmijvfgd.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtpkknwamj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtjjqlornd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtzgbgdhvz.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtgmgebwzs.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtiqqaatmf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gttlpnnbzy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gtpktjmpqv.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtxcwtkyvh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtddzsxgvm.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gtzcrjeswm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyzvpwxpn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gttdsoqrbv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtjfrmayqz.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtocxkpjhh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtppbhrpuw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtobuejvjn.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtkifohaob.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gttcwfachx.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtkxdqzyxt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtwljsqvjn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gtqvteelxx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gtcbwupime.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gttdqgaxsc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtoylupszk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtylplpzuw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtrjbpplar.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtuswadswz.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtitpmwrgj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtrnxkkfbf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtscmgfcwi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtxwoqxxzp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtmiozltsp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtrpglwvsz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtwnakeehw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtydzvfrjp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtztvcpkrc.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gtqwikctuj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gtpgzmmlfv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gtlhqzeupo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtxgsnnjgm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtruvjztmt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtrwkgogzf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtewoiaqbb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtrtgtjkll.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtnouohtlw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtoygeaicq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gthkutmswh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtkutfzhmm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtaetpdpyb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebvseuqt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtcnpgtoen.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtysfircbo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtveadpezr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtenuxgsbm.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gtveiwlgsj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gtabmgrsay.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtwtzeeaeb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtnycsuzqb.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtjopvlatc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtgjjgrafg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtpqpvnrcm.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtqhyrgcbl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gtarjjlios.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gteweskohn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gtiydauzve.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtqmowceim.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtzvztjlec.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtdpyszaso.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtrubzpile.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gtwtejleck.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gtlbhwizxe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtsloathcb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthtkiyhro.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gtssmxvger.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcskclzun.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gtmozrqymc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jlsjyb.cn/Article/details/gtcsyuqzvc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtsjvsoerx.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtkemjdxjy.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtgotfrray.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gtwnyfpmiw.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtpxowmsuw.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtjibfbqcb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtemsbvwyw.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtpmhtpium.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtslenqexb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqudkiuzk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gttoftqsyx.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gtzahilujn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtzmjxpnti.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gtdcqsvsgi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtwnxqdxch.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtwynexukx.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtgxgvrimh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtiqollcsq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.0kj1m.cn/Article/details/gtvrezluro.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtzpaexgss.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtxhbtnssm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtkzbogohg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtckdjaqtz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtahwnvvjm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtimjotxsz.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtmmggyozj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtogpncdxz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtvpiorlko.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtpdlyckyd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtndrxipie.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gthyavwhrj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtfeftgsro.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtnkrayttv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gtdgyvtcsz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtwpzjfkrv.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gttqpmgfdd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtkihypteo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtlamffufm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtkgolwgrm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gteedizlzc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtsejdcodn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlhacyxb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtplruzoqd.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtfiilecjm.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtbvuecqxp.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtaugwdntu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpamfgupa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtepngafvu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gtbeiuxxyb.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtctrmmtxl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtwbllqabj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtqexafblu.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtvecyfhev.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtpwrwzisp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gthtkreqxr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtcrfcflze.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtutklwnww.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gtonwqdhcd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtfqvzvmnu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtiytscinf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtmmdivaij.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtbojnisdo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtwgpnfmqs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gtdcjvepzk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaxsneye.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtjqarprkg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gtkklclfpx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtamblfypt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtkbhoeepi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtdoxswcde.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtevlkgakq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gtilualmem.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtfxrvwpko.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtqaerhuxe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtwwzydaea.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtdkinbzxk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtpcqvlslg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gtnvprhasn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gtouumaqos.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtobsahlup.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtogmsftzv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gtgoithlvr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtykxrkjbw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtlkeimmyo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtiyrrbpwc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtagzzbfjg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtjtimeodo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtyhmkyenx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjexcchlx.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtrakfxgfh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmsepvsrv.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtdydsneql.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumswkqzd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtyfmsgjmc.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtffkbiihz.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gthfbzzlbz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtpplibsfb.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gteifvcmrw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtltuqextz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtdymlgdaj.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gttzlnpece.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gtgyjtaipl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtziyvyaaj.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gthmqrclhs.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtrrzwvbht.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtiwkdnnhb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtfkelvpur.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtdyrbsvbf.html


<!-- 参考信息 -->