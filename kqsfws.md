代发 wailian999

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssmbbaio.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2twaaewur.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgrveejn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gt2mpjypphk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2zjsfwzek.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2iblirwjq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjykgtmm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uubpebmh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gt2zyffwdmx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gt2njxouymn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gt2wrjxlrnk.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gt2xqxbrekm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gt2oczkhpyr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2lponiokn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2skeueomi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2sfymwayt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2bultzqlc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2ywvyjtiy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmpabmhu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2defrybjw.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2ctudgzex.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2vwbwsiev.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2rnqihdch.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhuerwkl.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2mlprdylo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2isrfszmj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gt2qkbrjump.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gt2cvzciipx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2slpjyztd.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gt2okpgaqaf.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gt2dgpwzhnz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2lvlxduud.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2nwiggwwr.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2styucpxs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2hdilwgbe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gt2mpalmyov.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gt2nldlnfmw.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2emgjvolg.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gt2exlboatc.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2bzfspehh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljjpfzjj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2oxxhwwli.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2nbnqkhns.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2yfuzfmue.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gt2mnhvgmnv.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gt2ijtkiguw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gt2swkcgxrc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gt2qubgfuww.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gt2cnfwecty.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2stxltkgz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2tbloagdh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksnoilue.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2uetobeqc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gt2uzsbgwsv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gt2gsxzvwix.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvtilpmc.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gt2zsoneylf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gt2rgsjdeuv.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2fnuhsrdr.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2griyrval.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2sujdorjw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aoeffaye.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gt2iuqctvyr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gt2ewbwubkp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2ixluqsxf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gt2llrypvzn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gt2odnqqpsp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlfmynpf.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gt2lwejxzoa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gt2ovqrqjaw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gt2uitzilne.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gt2ainkdpoj.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gt2gnpslpnd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gt2mchhysuq.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2vwzywgps.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gt2xizcgqtg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gt2mmfeuuqm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gt2aenonfdv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gt2wskprdrn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pueondax.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gt2nvlfaqqu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2lajxlson.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gt2wtltptvp.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gt2vndsfcwp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gt2mtmncbqx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2urhljyrk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqvxvpvz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2awtwhgpu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2lzdgnoum.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpyejxjx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gt2gmyxsttk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2skskdarf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfkkjgtn.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gt2mdfritlv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2dqbtnwdw.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gt2ccajmbet.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2toqpkfhm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2mlnuolhu.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2kzraubaa.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ploicdrl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gt2ahraswdm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2aukvebiw.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2ebokiihs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gt2ntvztghp.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxzupqsa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2crkklhnk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gt2wgnewcuk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gt2bhfyhwrk.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2dkqerapj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2nnxjnuvi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gt2bqitsyfh.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2gngcmdbn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntwwrmhe.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqihzukl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gt2uxiehxgm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxbqvclc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2nrxonbpb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gt2jnykoomq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2plbrfcaz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqbuabio.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kugriwoe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gt2tvrpvnux.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqbevqvp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zekshdjp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsmsguu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2ffaanoyb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2fnkwjtnj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2cvbxqqyp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2vjxepgio.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2cpibfdis.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2uioevwjv.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gt2iklzfydl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruirkwrq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2zdqzbjut.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2ebrmluxd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2jsesyfva.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gopluhnk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2dxlntfuo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2vduqwwfq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2puykxyio.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gt2qbrpnunx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmcoriel.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gt2pphqfhzy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2nbqwiqer.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2rukpmzfq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2jvbnttdw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gt2umskfwlu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gt2zutgxjvq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2skpkdasv.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gt2cjtieqak.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnfrocru.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2mcdrvcon.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gt2bymmwkuc.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gt2osgrqqcp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gt2kabtluwy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gt2akzbsclq.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gt2pvpnlfxt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhcijtoo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gt2fbdlbuag.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlxzrwvj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvmlhsuo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2lgzucynq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2vsqbnfra.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2zcwyjwee.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gt2icnirldx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2gegevruo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gt2thiasrla.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ywhpqddg.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2drpbtxmp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2dumbkzcc.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2mvcvnzso.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gt2zerfluec.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2bnddrsai.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2omqnnukz.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2ydcsjlmz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2nruegrza.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gt2kqadchxh.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2yzkwvnwl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gt2dmyoctsg.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2zrmfvoxh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2bwhdvqzs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gt2ljaoinfs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gt2ojiccecp.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gt2ktezkzzo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gt2oirnazwg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gt2baftmzgx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2puuqzmhp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gt2dqvsgxij.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gt2nwdhjmxb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gt2otykbvdn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gt2hntafkwf.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2nyqiljis.html

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2hskavahl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2ixfaiioj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bslodllz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2scfqcphq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gt2cvzbsnsb.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2yfveatav.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2vlbsnsph.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gt2vrspmlsg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gt2ovhlijsa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gt2zczhhfxk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2xmuboiwe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2cefzvnmf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzlsuksx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gt2lkqjwaft.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njwalnrr.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmdmxxji.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2nbgtnwdy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2ereyfbce.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2hmrchtup.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2bukczkkh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2caadqglr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gt2tyqdbafg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2ievfzbiz.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gt2edyaacfh.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gt2totqszht.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gt2vtjxfoxl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2fwcqwfut.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gt2hhadjzbe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2kfqxjrew.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gt2lgtwuevb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gt2sziacbyl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2nnqisids.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gt2iyoooerf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2alsvfsme.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gt2gitkqkan.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2asdzglwn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2bbhworrm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gt2zmalcsqx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2sbngrthg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2ubokfbrv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2horijrps.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gt2ucjybekw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2rdqdutwt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gt2mpzqqhjc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gt2pduplqfb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gt2oofrpdya.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gt2yycwitem.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gt2shhlyovq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2skxctoay.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbwsmabb.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gt2emkdfocy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2vwjkwwao.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gt2uyxtwybx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2hphimqqw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2dnauooky.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gt2yjunjoxq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gt2zmownbvz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gt2wrheoioc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gt2mecextvl.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gt2vgccpwll.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gt2myhqmyox.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gt2jssanzfr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2jqbojwaa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2ovsvupmn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fidjtdzi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gt2oqnutjjg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gt2quadfigi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gt2oubcsmyb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkhizhac.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gt2qssvgwlk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2fogfgqri.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gt2zouuwszc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2xphlbljs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2jknhbsxw.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2hferxqfl.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2isyvyiqv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvshwuzh.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ivoodilr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gt2chkalhve.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfdpakhs.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gt2wnbvbisl.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gt2lmzaiswy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gt2dlgfdare.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2zfvdzrqn.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2sqhbfiin.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2yebqbcnt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agnldlnb.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2cfoxhgnu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gt2ihktqznx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gt2qinbmend.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lesukymg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gt2nngjbvdx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkyhvvna.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2vipftvfs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2elvxykpk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gt2enhhlysc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gt2jvczhwuv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2qeywjvxb.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gt2qblplccw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gt2nyksxqoy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cghwkwzo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2qwsbtqhy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2lknkevac.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2gfhymaqk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2exlemdtj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfdchqsm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2buqylfxl.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gt2ldmnwfgd.html


<!-- 参考信息 -->