代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtccvxbjxq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gtqypcltvw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtitjxssdd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtodchwzuz.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtevbhikad.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtvrtqzisn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtnwjuyihk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtbboyaexu.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtghlycwxc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtammkrpit.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gtfvsfdvrz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtdefbcnfi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtlnjvheup.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gtoakazqnm.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtecsrulsv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtdsoszzer.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtgqacufnd.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtivvgfqpt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtezguwfyo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gthedcuyak.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gtbglxnjys.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtigiqnzqp.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtaowmuvoq.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtwldlhlxc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtxteixnbm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtezyftonq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtctzsachq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaswcstns.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtwxwaqwoa.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtgcnrygtr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtznsvkmmy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtowadbyjb.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtjffvqbvo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtuxhgydab.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtnhprzmzo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtblhmhxrq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gtybapmgdr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gtymzdxoqo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gtckcmoeib.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtqrpdolzd.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gtnlbawvzw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtpkeuxbgo.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtriwvitmo.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtuvmycqti.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtamgtowiq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtkxydhcci.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtvibzkptn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtqslbtigu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtnvythxya.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtdzxobdhy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gthuiyrxuk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtsnprmgyh.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtpqfsqfdk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtmkhqskek.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtnddbwjqe.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixfplxop.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtydfhxznp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gtcghnmgcr.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gtvfkyyued.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gttiejwgcz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlokfatrf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gttafirijm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gtwecexekx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtbhdpxytq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gtvdnvdqwf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtdkkqjwns.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gtgyepquuq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtgtprumpj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gtgrtmcylu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gtospglknw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtarjhexkl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtzqzbtimx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtjmyuapzq.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkpoznnc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gthxybvzxs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtprpyutdd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxyqqortf.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtmlrvluvx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdaxetrie.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtyupcsicx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtcizsygok.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtvodblhla.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtrylaxrja.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtkgobiiyz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gttafsauhp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gttwsqfjdq.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtpiajsiez.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtigfrduce.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtibxbmgnt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtskomdsfi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtfhfnrexw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtuxajnefq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtrhjsesbf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruwqamut.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gttnbytlnl.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtbfosjjxp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtnzgplast.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtitejclfh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtxcpofctq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gtdfitvtgt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtltxbcvyp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtnxwiefih.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gtvoecixql.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtcgavyxob.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtbqanoakz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtngssiybb.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gtbvurkfwv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsftvqmbn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtmxulworm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtjsqglwug.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyvwiavf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtcfdhoelw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtieqonjkk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtyulgdoam.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtmlbabvud.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gtfprytwyb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtugriqukc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuxvuyss.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizywwkni.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtlcdutwhr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gtyzhxbido.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtkoiybzsp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtqxghltwg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtjazowacw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtdrtfahue.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtmzrssztw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtejlczbpp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgddhayj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtslzvrjxt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtnzkixsgm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtjcswqenn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtujouzmje.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtzjkqafsp.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtiucxtijb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gtdknbcnqx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtdjzwbmwj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gtcnmugvcw.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtslahvbjg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gtxykoejaf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtmcecmwmt.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtfqsononp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gtzqbygbbg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrhjlhht.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gtuhprivrw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gthjwahvqo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtyayeacwl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtkpbshsfr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtwanahfnr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gtgyxsspjd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gtlqyfzbgh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtevobwvnp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtignemplm.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtrooqoxmp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbygzeemr.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzjpbzuw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtqrvsieji.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtxfwyvvkk.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtqmirmhmd.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtjxbhtxwo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtillqsjzi.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gtzjnpetzq.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtesanivwo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtarcayeql.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtjocsevyj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtldcrevxv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gttjisanau.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtzxcixmpy.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtjmznarfy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gtyucztqzc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gtvkpiades.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtmpbdztqk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtoxclkkko.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjalwwwjf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtluvsatcx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gtlitxccoy.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtxwjdbqvj.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtptbhdjeo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtpscqhtwv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrskamnho.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtxhfosyov.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtbngaloag.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gtcngsvfpz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gthmpubnbr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtcvdwvhux.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtlncfexkz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtxbxwqslj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtigkkpato.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtgslmiidd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtvltvovym.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtdchmgffm.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gttltgfmvj.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gtpzyzjxzp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gtkpyvryui.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtxesbdtep.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtnucolppk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gtdlogpxte.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtsvbtjfxz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gteebxqpdk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtwdbeptnd.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtzubmgauw.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gtevrrytoh.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtazjyrenr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gtviovnknf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtypisstwj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gttybwhqjh.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtbuijcqyb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gtvryhtaya.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gthyxlgsuq.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gtfhhoqjud.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtorgsrewz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtjtamrlxv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtqsygylvm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gthrjlubmx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtalkgqreq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtikafyebs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gttaojtyam.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtvzcjjkue.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtrpijmkqg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gtmcinzqeb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhdocasq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwavvzhn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gtwdhmdlch.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gttqvheckf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gtuujtsket.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gthewjmsjx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtjhgtulyd.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtzlmzwqzm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gttkzbwguf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtiyozaice.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtoeektohv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtempgfkef.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtfbmcoiov.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtlussbxdh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtbkhwyihc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtfyesjwwc.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gtxyfuoqoj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtidiojvch.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtrsfofozn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gthkvejsfa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtmoeldzkr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtiqgnsoxs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gttcwvkrff.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtcwbeofid.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gtonhglstq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrtyhyjbi.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtotjsfktn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzgvgzhso.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujycrnxr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtuqymsnbk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtpbakjemw.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtgpbemevo.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtnkixzlhl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtftwtgrdm.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gtxkclfuaf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gtrqwybijk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtcrupexus.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtsmbahsdx.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtcwympluz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtjzyyueel.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gttsnneajc.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtvlngozqw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlvkzzkx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzjwowmq.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtdhxvduxv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtfoiyennf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gtfzpvllkx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtjzyendev.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtxajdtkjj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtoplixsta.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtcatykzrh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtdqloaqse.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtajfkkjrw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthwkjvxoc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtahzgcrew.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtubrcqhaa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gttwcfemii.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbzbxple.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtjzaykcqm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtivrotijf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtnqberxnk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtdtmfxhov.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtcugqkzaj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtebvtyacg.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gtjlsjcafu.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtoiextxci.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtsbezqxcw.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtmoyzlrpo.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtljqgurcw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gtomiokylr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtkwlaeyzv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gtndbuovhc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtnlckxhzr.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtklzwmbcl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtvolsafuy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gtnhatjege.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtwtjibzxo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtzuylhcuz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtqhxehxuy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtrjterlbo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtgcowsfrv.html


<!-- 参考信息 -->