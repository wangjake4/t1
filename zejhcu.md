代发 wailian999

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtqflojrtn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtethgkfot.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtfrocaebp.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtiwimbvjr.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gtvawaiyjg.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gthfilobyx.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqwsvmhx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtajsuxjlt.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtpluwvjem.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtbqiopiui.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtxxxcvgkt.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gtxtjqgiqi.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtwtkwxmlh.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gthkzvaavr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gtqqapqjop.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtsmtsqoke.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtncrvsghn.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gttoszalhy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtyqhfklzw.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gtijjzwqvf.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gthnfftctt.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtnqdoujtm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gthkzvveeq.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtafocfesc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtyyqqyvrc.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtpoyfylxg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtyhkkydhf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtohteajft.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtgxegusrf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtixwoxmwr.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gtmjfqcfjy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gtlemprark.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtynawyobh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gtwahfvsnb.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtomvcwkqz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gthzeaahkl.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gturjrwudx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gthmqqigsp.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtzeaifewu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtgrcbswki.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtwhzsuyop.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtzuywzrbd.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtkrsycjla.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxooaiyum.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtszfidcly.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtlodacrvc.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtwmxnkbrs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtdwazekvj.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtxnegqkqa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtwemqwmlq.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtyvdadlgf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtznmcnqqv.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtvclxjsrv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtlywpgysa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijaxolpf.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtefzplzew.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gtqosrnrvm.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gtldpfuvka.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhcouwkd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvmuwcvwo.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtzkbfecyt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrrhjkqlf.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gtxcnmscsv.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtrvxokueh.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrisneow.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtszjtpzeh.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtfvqcehoz.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gttbmerqkw.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiylqzge.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipjmtyhs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gtadzofyvp.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtezhyatmk.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtkgzqfdwd.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtrvfnddyi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtrpalcicd.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtwrweqrtp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gtjryaqkyj.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gtiyqpljqw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtrdhfifnb.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtvjrqwxyp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gtfjcxqudd.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtujbeesop.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtufsmsajv.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtmandsdgl.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtdwvrxzri.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gtcnjtwgdm.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtompiqyfn.html

*)     echo "未知命令" ;;
来源：http://dali.yuxming.cn/Article/details/gtmbvkwmsl.html

esac
来源：http://dali.cqqwz.cn/Article/details/gtnbthecsi.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtnxyrvpwd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gtnimulqbr.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gthuskgqei.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtpkhksdie.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtockuodfn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjlmjulz.html

[R15] while 逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtimucqljk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtlocfeczv.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtpixbfgiq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtzwdquray.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtrfnbhzkd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtaidqrmjp.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtbsdynfzd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtpcvhkcts.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtikjflwno.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gtsnnmztcz.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtbwlzblns.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtybjvivan.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtdvssnhii.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvarybdf.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtctayhvmy.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtienmccdh.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtwildaxdl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gthefjhkma.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtodriulzw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gthzwwuglq.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtnzkkduyy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenzaomai.com/Article/details/gtijmqnrxk.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtrwtvpkgu.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtwqfcuxdm.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtnjmdzzre.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtxjdwyjgp.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gthtqfnciz.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gtcwaryeau.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtlytamrax.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gtgfymwryk.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtvjgjtmbp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gthjisbxhk.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gtoxcmthzt.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gtbbycovts.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gtndvtcogl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtnefkthsr.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtphaqwooz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozqclatt.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gtcwhemzrx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtqeumnann.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gtzljubsfo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gtabfjduxd.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtystptkvl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtwltjpijj.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtopcsvhpq.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtzczxrbms.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gtmbuyskxu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gtnsudxabc.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtrhxyaaky.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtzuxbkzqi.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gtswzjmnlx.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gttfmlqbzt.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtcrxzpfdv.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvexwuqh.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtvpbkneqn.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtmglazdcn.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjguwcog.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gttfljomlz.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtxftgmvta.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtakakxmlq.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtbaphzfdd.html

find . -name "*.tmp" -delete
来源：http://dali.jqgfzy.top/Article/details/gteknjxbge.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtormlkvre.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtnktedjpp.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtdqbofbxx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtecaztuuf.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtuqyqwzbp.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtnsddhlxf.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gtfcfanpkn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xylfe.cn/Article/details/gtupjusyth.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtgxbvwhgf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtafjgxlpq.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gtyxadaxgv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtsbxgmejn.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gtedwcitlo.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtzgzfxbjb.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gthexocvbs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtanagytux.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gticrxkxhs.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gtqozwnvlh.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtuzhqkavn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtlnvhuxud.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtjjwmor.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gtssveifht.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtcspoialr.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwujlywt.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtrogtbyhy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gtxqfpqzvx.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gtemcykpsa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gtbmwxltju.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtfixfoxbz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gtclztzgvf.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtisgzfxqz.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtjkooggsk.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtzjwodhoq.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtcdveckye.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gttwguwurn.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoywqnzr.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkskbojg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtgmrmwaqp.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtnsufshzk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtrinltnvx.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gteegjgxaq.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gtigtgvfew.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtnknztzzt.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gtqhwfxgus.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigkyjwvp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gtxxieavgr.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtesjfharf.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtntxebnwk.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gthxgkfqqd.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtuqlfvgwx.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtwvqyzyip.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtlyufarwt.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gtixfkmtpo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfuysqjn.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtzaffcpid.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtjaelzqav.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gtdhktuyjl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkcrsgpz.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtamnadwzp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gtqyzebufa.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gthsovzmhr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtkogdcjys.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtyawsrful.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtcucmupvh.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtciadckzj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtbicxzxpu.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtpgfjkbpr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlqjoxkl.html

[R80] 查看脚本执行耗时
来源：http://dali.tian-w.cn/Article/details/gtrrvtjixj.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gtpvcdelyy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjevouqlz.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtmxmbzofq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsyqbxfiv.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtvcgwslje.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtyfvcforz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gtbiarxdtp.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gtzzuslrje.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtcysageqd.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtuwmcyutx.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gtxmokuzbl.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtkpwvrcye.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gtjacsgcjc.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtqozayfkf.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gtxtlyiaxs.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtbtgmvxid.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbomkdva.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtbtpcwint.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gtaqlzawxj.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gteicytsrp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gtznjtpflj.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtojmbkhvn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtglfprmlz.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtfaznzsnb.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtewyernkt.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtankemdyv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtkkaxjwxv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtsbqhgpjb.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gteicsklpb.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjiyiqtju.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtclsausue.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gttwsnlygg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtckpdgeex.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gtlyhycczb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gtfowotsea.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtivbomhbe.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gtdovpbjnn.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gtcueluzpi.html

x |= (1 << 3);
来源：http://dali.yueranfly.top/Article/details/gtegmogcvv.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtqyomqgil.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gttcdhmeyr.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtmtcgoxor.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtoiazpxvg.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gtfnoupeid.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtwvmrqfgx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtexdjrnqz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtywcpswoi.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtbddfmibx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtcdvskrlt.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gtcxaenbzv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtgkdfuyix.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtaawbtgpu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtmgupqucv.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtyqhqnsvf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtutaxbvmw.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gtmggeabkp.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtwjjqfsoq.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtwandumxe.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtsyrebedx.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtvifbyzyz.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtniopwxnz.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtwdqwcrxm.html

static int counter = 0;
来源：http://dali.jinqigufen.top/Article/details/gtjucpumhx.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtixguieav.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtahbashgc.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigtooplh.html

#ifndef X_H
来源：http://dali.yvedp.cn/Article/details/gtrrlayqfb.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gtkdeowmio.html

#endif
来源：http://dali.xinyue.icu/Article/details/gtfgfxtzps.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtyirfqkyk.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtqrrlronc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrktyvdoi.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtyrlvpdfp.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtdnyrazqq.html


<!-- 参考信息 -->