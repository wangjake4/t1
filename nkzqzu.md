代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gt2gcmdwhms.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gt2garxgand.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gt2xwgnbbji.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sulgjtxv.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gt2huywgctj.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gt2ffrwraup.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gt2ggxrfsak.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxrykpsc.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gt2cccmhnmx.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gt2qcmbmewk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gt2vqmbpyhq.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gt2jaslovop.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2grrepoom.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gt2yvhrekaj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2cnczhlgx.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2kojiiwpc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gt2jdhydsib.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gt2refjabmt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2zyzbnkcs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gt2ucknndfk.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gt2svtdauls.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gt2hnmizndb.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gt2vqefjttx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2ajqcxizg.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gt2lhzbcdad.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.havefunace.top/Article/details/gt2oafqisdd.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gt2tqknjhgt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gt2cznwwnpn.html

[Q80] 字符串截取
来源：http://dali.sxryk.cn/Article/details/gt2apcqzkpi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frrnkbwl.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gt2agkwpooz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2frlolyuu.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gt2menlcjnp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2blzckwif.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2ppodobff.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2ugzblbjk.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gt2oulhvvun.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2tikxkvzx.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gt2jncvdyqv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gt2uzeirklq.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gt2fiidmgrk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gt2sfskmprh.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gt2hdaisqrw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gt2jhnygehm.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gt2xqnymloh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gt2peosggvg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2mlhyoxfa.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gt2njeklfll.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gt2aytnsalf.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gt2uywsvnad.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gt2owswvfnt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2aupmqdae.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gt2mafjvshn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fgqotzsl.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2ikouvvgv.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gt2clalkhsa.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gt2wihbmxbs.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gt2kpydxibv.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gt2qwqkeoqs.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gt2xlubheqo.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gt2sqienpqt.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gt2ytniisyc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gt2vocxcreu.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gt2dszbichn.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gt2thlcdhtc.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gt2ssjuqlgo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2vntfnczl.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gt2wgnghmrg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxpvprcx.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gt2idpetkzw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2qzwvalsj.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2tarjnlky.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvajztqv.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gt2undjiclf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2spxgtbpb.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gt2iswsssgf.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2akpxldph.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2zgeptqji.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gt2qedjlacs.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gt2uiupgbxt.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwbcaxln.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpndddlw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gt2blrylqlh.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wznoocxu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2tpuuzigs.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gt2aiktdqrw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2lxbvxriq.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xuzollpv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gt2xuwdqciy.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gt2eiykeyav.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2hvuyvkge.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqddxsps.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gt2qakjenqh.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gt2amyilywx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gt2wlivpayj.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2bmxiqbvg.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2izumkmcw.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2nljkrfxa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gt2apmejrxy.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2yxjhuknl.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gt2vyybybzj.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2dodaebdn.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gt2mhneitgs.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2unxoxjbf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gt2oeyfhreb.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2lbmgwjly.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gt2dqtphqnd.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gt2qaldlitv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gt2ocwcrhpo.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gt2meengjmo.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbhklruf.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gt2vzioevwj.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gt2etfjdgwx.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gt2mygmvpgw.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gt2ghsjmemv.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gt2ymdfuvrg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gt2mxiudgtt.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gt2oxtygsza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gt2dlpfmvfb.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2yyutirbs.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gt2dssfttqm.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gt2uowgnvlk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gt2ftfwxepr.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gt2kukhlezt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gt2zwwauqdk.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gt2emafrqds.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2uzdlryuh.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gt2pyubypqb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gt2zcrdmfcc.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjfzkdrj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gt2dirzhnla.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlauzpy.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gt2hmlfkvwm.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2ulxjktdz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gt2hyxarpob.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gt2jiemzqxq.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2ozlfzhhf.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gt2hemgdxjj.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhfarzqe.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gt2ahzngnfy.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gt2sqagmwqk.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2pmezplzg.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2jayijqjp.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvdxmprz.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gt2raevdtml.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2mzpsfmqp.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrdqhcvz.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gt2pqmaxesy.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gt2rclelwja.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gt2owzvxcdo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gt2xopcljfi.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gt2mdmqzkcj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gt2qsvsenea.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfnnrsxe.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2hulikkqs.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gt2eizwwrno.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gt2bouwdikv.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gt2rzxpxtrn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2ptluletc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfmvois.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gt2zxlsiulb.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gt2mpuadjjt.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gt2njwknrvb.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gt2rulpywjd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2xibxylle.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gt2flqwvxzh.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gt2seoxpwyi.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gt2nazbsome.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gt2zhprqfmh.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2gtpiqpbx.html

scp file user@host:/path/
来源：http://dali.xylfe.cn/Article/details/gt2hotobfty.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gt2xokhztcr.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppbqksgh.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gt2okpkivtx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkggqywm.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2pbfksayx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gt2ewrfzlww.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2fkxtmyen.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqwdhyeo.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gt2ztnehhao.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gt2cpiuynwy.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gt2pxpcipyy.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gt2jepqlrza.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozfbhrcs.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gt2pqqghcpi.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gt2gujuzqoh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gt2iwograjk.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gt2fmvshwnb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gt2xeipzapu.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsavrxkp.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gt2xsrbaxnl.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gt2hpedemtu.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2ypqpgkhh.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gt2dcxrhozo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2kqnzxnhe.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gt2yusazrmg.html

head -c 16 /dev/urandom | base64
来源：http://dali.yongpay.top/Article/details/gt2huukkemh.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2achxqrhq.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2ulbmtook.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2kjjmwtqk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gt2ilnirfak.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gt2vknddxmh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2wdsaakmt.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gt2wqvcktmx.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opeynxdv.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gt2cgyqcqxf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2dyczkpiu.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gt2vzuncsef.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2bhaawspx.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gt2aovlcqtd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2rbvociof.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gt2qdslmrtm.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gt2zyixhowz.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkqgztmh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gt2trhfflww.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gt2sazzdvou.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvmncxv.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gt2rpvfjzbe.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gt2vdccwbox.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivpjdzqz.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gt2bioqzgfv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2osvnzvhk.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exijofwy.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gt2uckamewd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gt2bxxahxft.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2asarsbfo.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gt2kejrlcve.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gt2ojatgplp.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gt2vsngjixq.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adjndxle.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gt2mgwvybqr.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2oaqjmdqz.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ujnqubvw.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2sdgkugpj.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gt2wttjjzyf.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gt2lgecfrmt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gt2drfvmmof.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gt2dgrwadaa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gt2sznnrpvx.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gt2kcqytpwk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gt2zwbbjzha.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gt2sljltnyl.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2vvizsxks.html

[S11] C：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2mqcttqlx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gt2fwpicyoy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2muefdlzw.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2uphhoxoc.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sahaqulm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2gkefvqpv.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gt2idyktqve.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2rujuuhup.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gt2ddqihhfs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gt2tisupzjd.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2kxjizhzz.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gt2cyvrlpmb.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gt2foxyrawg.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2tartjuya.html

[S17] C：安全拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psdqrkhu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjksmimv.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gt2hmialgha.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwtlpwnb.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gt2rwfbtdco.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2msfliyzf.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gt2gwyzgnkn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnszsbja.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gt2enasruje.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gt2qnxjhcsn.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gt2nrkmreqq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gt2llsifhpc.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gt2szvzhkll.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gt2wxebsjsb.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywuaawcg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gt2xkqvuovh.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2cldabafe.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gt2lprmkahu.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuidfwzo.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjtrtawr.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gt2khktgqbi.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2hvnxvvnj.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gt2byyzrkwf.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gt2dvisauqn.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2qxrbqwyl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gt2dpjlziok.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gt2babxtzoh.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gt2nozicjsc.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2bmkzllim.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gt2gpvijbqr.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2zljeyabq.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gt2dhtiseeu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gt2icavdjke.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2kujflstm.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gt2qifpbewk.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gt2urgmnbkf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gt2waogrcoy.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gt2zuapajru.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfizmcwl.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gt2meojubgv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2hhsoysbg.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gt2pbnfwyks.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2punymlvo.html


<!-- 参考信息 -->