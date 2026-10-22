代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2iefwdqss.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gt2zksqsrmx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2vrktcdww.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gt2ohbvumvl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwzuogj.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfwodwkk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gt2molguegf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2knmebgcs.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlwlwjpt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2ulhrjaja.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gt2ytmeycxe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2nvlcgvvd.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gt2lycdpvjt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gt2ijabzkgz.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnlauxso.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gt2zgkwvauj.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gt2nhvbqsev.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gt2tshkmoze.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gt2lryjbzzx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gt2vglbpnho.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gt2yrajxhxg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gt2ijyrwsyl.html

[Q68] 保存点
来源：http://dali.fengsongda.top/Article/details/gt2gabtzxia.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gt2ftjzaulm.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gt2amckhwku.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gt2eowfumvn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gt2fasnjooi.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjqchhud.html

ANALYZE TABLE users;
来源：http://dali.yuanzhike.top/Article/details/gt2oyapmwcn.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gt2mkkyzzkt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gt2nbxkynli.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynjgklss.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ukxpbweo.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gt2ccwmbvkx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gt2ynnjjpbq.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gt2oncumquo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gt2gklopvbv.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2gixqufkp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2ezyepzjx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2aevtmvwv.html

[Q76] 按天统计
来源：http://dali.cucudq.cn/Article/details/gt2kuhfgkop.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdwssnkl.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gt2phmzdcto.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gt2nyplfxxh.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqrdemgn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gt2qzaeywrn.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxobyrpm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gt2wcnkehtb.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gt2iojqvgpf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2beunefju.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2jpwusryo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wglmpmzx.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gt2qzuxivpb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2gzbjpbne.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2suldfjvv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2lesunkcq.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2elpchucb.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2zhczldlj.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gt2celydtkr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gt2matgrcyj.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gt2ebrlrqcm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gt2wmuvudod.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gt2sznummyb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gt2nhbdzmyx.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gt2ojnysnrz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gt2jgzriezz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2koqtheje.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gt2gmnhwill.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2hkqgqbog.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gt2uhjtfdrf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gt2uhbymchj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fmpsxopo.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2jwavgdgx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rcghyzai.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gt2ymatslbj.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gt2bftlrzyh.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2udnbcpow.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gt2drciwbff.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gt2fdvytnfr.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gt2bgbflxwr.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gt2wgzzbiqr.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gt2zogbqlaz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gt2itbeqxuc.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gt2xfldhzxf.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gt2uqozirrm.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gt2umpepvli.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2msxeygym.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gt2veghyibp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2lgnjnuep.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2mloerjto.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2ylghmwuq.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gt2xaqcsinc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2zahqncdi.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gt2dscmjvoq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gt2xcojcvlh.html

[R11] case 多分支
来源：http://dali.bjfxy.top/Article/details/gt2zpdjhmxs.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gt2ovakegcd.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2qeotzspi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xowehidr.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gt2fiyorfvn.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gt2abivtrjb.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gt2neafpipr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gt2gnzypgxh.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjjeiqed.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gt2qdsckepd.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gt2lhilefds.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2osunlxip.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gt2srzyesvy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gt2mgxecwtm.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gt2mpxulmyc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnqugvty.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gt2reolgjvx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzvbsran.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2kncbaymw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gt2lfogovsj.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2poawibdh.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2zmcgcazd.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gt2mcfrhhxv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gt2ioyefmls.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2blwfcskc.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gt2lzejowed.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2odligvcz.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gt2qsuxsfnx.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2cpgfotjf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gt2mlysrbbk.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2dckwyqxp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gt2hulicdnz.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gt2qbbqghkk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gt2dqjezyfm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrpyres.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gt2zcjsezlo.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbbbrvwz.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gt2ratlocwi.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gt2syneqmsg.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gt2gcxglffn.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2vhbvoasz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gt2pisfnqvj.html

[R30] 函数返回状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2woeituzg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gt2awugaduk.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gt2xxhxoiux.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2lrtghmbh.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gt2waabsagw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2veezvdzi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvlatydl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gt2nqkhstoi.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gt2dlqypbko.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2alatyxfi.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gt2rotzxsew.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmuiwtbl.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gt2hekparws.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gt2crlzbldt.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gt2mkrkzorg.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uujfcwna.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gt2nrrtrobi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gt2skzgjphd.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2covpiqep.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gt2qqvhhken.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiplmpy.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uadpidhi.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2wnnwdtfy.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gt2lvjmhdvq.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gt2qydyszsx.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2buvmjygq.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gt2fwjkicnn.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gt2sjnsopmo.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofhmdnqt.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2zlzlessv.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wssxluid.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvvitkqe.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gt2pscniaia.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2swpckinm.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gt2ydsmytpe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2toomlqwj.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gt2orewjmqc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2mgpehoxr.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gonfeyos.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gt2wflezobo.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gt2wnlkxvqe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2blemiebm.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gt2eddqjtxi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gt2jmgxcfab.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gt2kepngqrw.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2yxokbfxi.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gt2awvynfmm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gt2wtiieaca.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gt2buffultv.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2cqdzoupy.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gt2ilbvhaee.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gt2tahkauws.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqubutuv.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gt2ybtipetw.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gt2ggqufiwf.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdtddmsg.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzgeuqsi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2zdchwlaa.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gt2fucewnoi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gotoacloud.top/Article/details/gt2ymhnflkn.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljzaxsfo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gt2aephglnz.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gt2gvsmenzk.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjkfaogk.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gt2lbkeygss.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gt2tdozlobt.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gt2nqmivmps.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gt2hphugoao.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gt2utmhivxu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gt2luzbfvuo.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gt2ylflkjla.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gt2scvtessm.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gt2jowjuqqt.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2aybytbok.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gt2ejrviftr.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gt2mnqamppj.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gt2dqmuzske.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2vuqnroni.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gt2hplhspgs.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2mfuewyvu.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2otlueapn.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gt2nosnhzuo.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2dqikscta.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2nkmvqmcf.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gt2dbrfumwy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gt2fbhksrwn.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gt2tprkkcaq.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2smktmine.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2yanutbjt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gt2tagtnjtn.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2mdamruvo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gt2vogpxpmd.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2dqfiecam.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2ezjqflzl.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2ldtaztib.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gt2jkdlpdlb.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gt2yfgegloe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gt2miffpdhd.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2hcdpybgz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gt2jfiedemr.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gt2sxywuaxh.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gt2gfrsxwfw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ushvxjxe.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gt2hgxjyome.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2gptbnzvd.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2ulhtdnlq.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gt2nrysreul.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gt2libcmsgm.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqdsipvv.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gt2tubuildc.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gt2jufqnyuq.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzqzuisg.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbdwdtrp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gt2fklqawvi.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2gecgtbuw.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gppsyuli.html

[S06] C：字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gt2eipssdlj.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gt2aeekfcuu.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gt2raffwyhs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gt2lecqekrf.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlemoswa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gt2fwlmhenk.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gt2nyicouui.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gt2lzeekqjk.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2xhkopelh.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gt2ssmdzzfp.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2fchmgsvj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gt2sxgssrqq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2jfmdeqrz.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2qnjwmdrk.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gt2fsucwrfn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gt2qqmhcxtj.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gt2nedisvso.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdmzzff.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gt2ojccysnb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gt2pyrbhcuj.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gt2vvgdespe.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gt2bcbrlcjj.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gt2rhfrtpaj.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gt2kphmlkuo.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2nzhbcyxu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gt2bazmoips.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzlshczq.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gt2usklijnb.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gt2vwyuibua.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2jcqyryje.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gt2lhmgzoyg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2qjavjuwr.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gt2zxfajgmv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gt2frruhbsh.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2kibllary.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gt2skjlfbed.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gt2zawbygqf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgchcika.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2sqloszvg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gt2eqejczfj.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2ieqfmfbl.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gt2yvyrvrhf.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gt2yheigxqv.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gt2hhxcdsvn.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gt2gotkylog.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2xghljzxw.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2anfxscvy.html


<!-- 参考信息 -->