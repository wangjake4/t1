代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtvwvobswv.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtghlulddx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzhgaitt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtldausrdq.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtqmowwcll.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgtqzkiaf.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gtytstofqd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtxvwzwopf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtrflquizg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtsgthhtui.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtxgvjiovl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejtdkply.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtyqgooysn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtzfvgssvo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtvuvwljpe.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtdcwvwjal.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtisnwmoto.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtdykplgcx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtbaqqitoy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gthlcbjixk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtpzdxesdw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtozvtbcjz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtgwkffrua.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtvowhbxin.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtotrxqshl.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtnbafzajz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtjifqcduq.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtderrmgtr.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtviuiyvuq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtgcjweddr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gttaixbydb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtlupgolkm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtuadpnyzs.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtvxigjhka.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtbqjimooh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtokdeddqn.html

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtqwamdwly.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtfdvjdhsa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhuwjios.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtyfdrdidd.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtduneozbf.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gttccrcbkl.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gtdxdhpewp.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtsvhwtotk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtwxrhenqh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtoedcgrgq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtedjcrjzw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzhggzug.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gtsnwhghaz.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gteyhepjta.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtllidrmrm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtpkftprbb.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gttnyazclq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtbnxkkkar.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtygtroxyk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtsrpnssro.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gtxnqczhxf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtzngjllox.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtotcvebaz.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gtbyuezbla.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtjjgdqttp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtqzwfeitv.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtfleglism.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmtpzhcv.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtihqjzzle.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtmovuqwna.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtaktulcug.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywayufmz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtoubsgjgb.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gthritrrku.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtdkjncded.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtgiwpwzxb.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtvxtgdhwh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtmwpcskan.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtzkkfviws.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtfvewugtx.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtislcdvlk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtojpuuhji.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gttvupnapb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtebtdzcap.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtduzlkwul.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtnvpfryjm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtbsmhdyvk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtpjgwetxf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtehthqedi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gtxwczyvhe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtnxzyptom.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtykdkfagv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gtcbjtirvx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtabbfvmic.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtlgoflqjl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtndemgjul.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gtsglmixmx.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtpkcipwrt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gtcqsxifhl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtnfomwgqm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuqjqwbzw.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtqkmbcjol.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgdybiqfq.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gtjkqtijph.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtbetpotgr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtavmoeqfv.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifuwocnk.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtoqpxqdun.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yonumen.top/Article/details/gtrtyeelmq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtdgxlqdsa.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtcvyegqto.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtzlhabkns.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtsekayeyb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtjqthtybt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtutbbpsof.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtuxsnzifm.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtwpfuhvib.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtypnrjcmi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gthakzjsym.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gtabkkotnj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtsmdbfofx.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtlayvgkgl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtwjvoqfwi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtzgngfzln.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtxhkrnqvz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtmhbafcii.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtkkanjmcg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtrdhmqciq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtbtkyjvef.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtnfkbxywy.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtabonhdyo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtkxieurcm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtsebtojdt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtpckvbpea.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtzwpuyass.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtxtnjqpax.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gtvslusxlg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtbdqnxikj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtslgpdaml.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtkhyebbcf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtqjktiveg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtntcinjws.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtdiagrwuj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtzgtcjuiq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkxbrzat.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtkehgvswb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtwjialuwp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwwsuqwb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinrkmpou.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtqfasnged.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gtfgcbbiwy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtydwaxxcc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtaohztdxp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gthwxhpnzy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtzcdfjgzu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gtfdnfmevo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtnktudksi.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gtnnfejofz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtoptzmgsx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtyhzwaoxd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gtdyfejkhu.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtjpxrwvbg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gtaimilwbt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtmvnzzghr.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtfysueevs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtwpyvxizj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtbtfxsuqd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtmydbamnv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtrmvuukbu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtbjigrhvd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtcfaxdjcb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtvhvnzbtj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtymijcvvt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtyzbbdzno.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtgkpupoxy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcjfyiexu.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gtendfugij.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtoixqizbo.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtycahedtm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gtpbdvfxxw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtolhoywxp.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtesxqqdxr.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtnvbtdtcc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gttfcohclc.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gtgeuwbwdj.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobhqtyrr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pycfn.com/Article/details/gteimdwppx.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtryecqxdf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtrwusznes.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtadqtaogc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtcazfkeee.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtxelpmnwj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtvapuutxg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtdcdrezfk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtlivlhgxr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtbzcmnubv.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtlhlorwhn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gtmypgislu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzywfdgz.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtkwtpiyth.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtfwibrqpr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtpawrcsyb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmscygeb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtsenrzdxw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtdruagevc.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtprqpwcyy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdgjmgia.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gthiwcokch.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtzqdpjpgh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gtfcqkyqth.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gttlskglec.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtufaxiuhv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gthruryfry.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtmhsvrcyv.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtmrnwswcu.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtdpkqzcqi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gthuheohwm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtiryjybll.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtahfwavja.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtvqdxqkqs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtgaffjbqm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gtdljfsafa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtvamwyodq.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtrzmheqfq.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtdwlmlvwt.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtojuvlgqk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtxhlzjmll.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtfzzfwhik.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gthciewkdx.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtzgcmllgd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtkyxibykx.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtliyaywyg.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtjscycbje.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtgbvwrdtg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtvnglzrsi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtpsjrqfxg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtxmwzliwt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtgwymowgm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtnyxrvizt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtgksnapqy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtjhjkzfzi.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gtlppkobhb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtrfpkyzge.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtniyoiuen.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtlcfffrcc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtziohznac.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtitwxhgzj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtwgtldydj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtzuasifah.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gtpveyzjiy.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtiokzeada.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtcuhxmgll.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtvzftirvv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gteicokpaa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgtfajuk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtmfpifyev.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtaxsnhqqa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gthtlzmzom.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtwdnykcpt.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtrlmbgoxq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gtrddfjvzo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtysempvep.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gthivjxgja.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtlrqrqvdo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtlgwjbpfm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gthdxybvuk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtbojdwsrm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtvdbntyaw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcrckggsb.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtzcrimhnn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtssbnavut.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gtqwdeofpo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtsthlmgcz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtwiypakrm.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtgslywjgx.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtfpyrecin.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwjvkaoa.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtnuqsnlzc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gtderhsvnr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtteuvhcug.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gtaorzphhz.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtdzgextyy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gtsrynxxma.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtdzyzuchd.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gthtfiefld.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtbyafcynp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtqdzdwobc.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gteqtoklga.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtpekubuat.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtqpxtkvjx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtmosbfqcl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtksgzbmxm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtqjpdbhfm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtxmtgxhnq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtqxmwrhrs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtfueoafrb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtxxdffbpd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gtimbllaeq.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtvqypeprr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gtrbxxfujh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtrvfpohmz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtyoqdbqot.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtwxvpfjbb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgahxpfet.html


<!-- 参考信息 -->