代发 wailian999

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gtlmsapgaf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtcvucuupd.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtmpbsfj.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtjqyrtnna.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkasgjri.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gtjutiqwdu.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjclmcqut.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtefxwmmae.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtozwqcllv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gtenllkfzc.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gthmzrkqim.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gtptqvxoie.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gtbbuldqco.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtshodxfxz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gtpptqktcx.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gttwczdtou.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gtcfljmeoy.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gtacqsitgr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtsxthwgyl.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtvaqvlssf.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gthryfdveg.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtytawqlpo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtlxtmzehc.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gtjayfsdwz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtmzpiwoht.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtjmlplpxj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtryjgqqvd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gtoxbcbkhp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gtyjsmcvrf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gttadbogfh.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtbzggjyxd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtbfbldnyj.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gtnfklczhi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtdlawbsmz.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtqclftsld.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafniakwq.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzdivfgo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtitzxjjew.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtytkfnqhh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtrbcotdbd.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gtmnyybrsu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtyonduzmk.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtbuarfrri.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtqncxifxr.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtoaxlyhjf.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtycjtpztc.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gtzwrnungv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtttuegkow.html

[Q86] 读取 JSON 字段
来源：http://dali.vqdsnc.cn/Article/details/gtjjlwnyra.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtnlkczsav.html

[Q87] JSON 字段做条件
来源：http://dali.cashguo.top/Article/details/gtiuaqlkld.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhpiwsas.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtnezumoab.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gthxxperyk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtcciulqul.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtlotadngm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gthenjkmvc.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtmjorkvmn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtclwcwame.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwhdxzruq.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gtwpmygdbu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtevlozfdn.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtfxjbwepk.html

#!/usr/bin/env bash
来源：http://dali.0kj1m.cn/Article/details/gttiphzful.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtsrcqdpan.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtgcbsmhcb.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gttternkyq.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhbhyigh.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtqbqxeqzi.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtcaxucndg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtufwjinco.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtaiaiyfsa.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtkoyhplnx.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gtuknpscwf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtlpfljddz.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtkcxeotsw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkbcprxi.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gtkqeeykzb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxyrfymg.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtxgwiobfv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtgcvfepld.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrknivrgg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtivetzsyf.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gttvrwmzkp.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtdrjhssee.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtnwzwdbpr.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gticjtxsgj.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtnomynvgp.html

esac
来源：http://dali.bjfxy.top/Article/details/gttblrieua.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtchuzhrub.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtbczwonpz.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtaphzqcto.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtktcjorku.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gttbfbovda.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtiazpnvqk.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtssjmttrn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtehnndscz.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtibjmawmk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtoltjyrqk.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtcdisgaqv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtmzckdvoa.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtqpaathbg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gtwsajqesk.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxtlxtjh.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtpllfoaws.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtmosxziyl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gtcvdyylcu.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gtqxvwhuac.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwosjhtxd.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtcigbjspg.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtoajesbje.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtfzwigcnl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gtncqeprfo.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkwcdpnk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gtfvwffvzf.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gtyrakbrft.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtijgmkudo.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtpfszlmga.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gtolkguvlx.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtcdekkico.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gttsdtajzx.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gtqpypcxha.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtxcupqaqm.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtzlfvnlpq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gthbhwvjvf.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gtboxljvjd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtflfejrcj.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtcesztskx.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gtgucbhkfx.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gtetcwgzyb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtnoefvrpx.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtsankabjp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gtrrrwgczm.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtgbfdvxry.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtatprseca.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtksryisqw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxinkj.top/Article/details/gtibmspalx.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gtsygrgsgu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtlhisbnhr.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gteavacwpj.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtlwylzzso.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtzbvoeojp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gtheqclqln.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtckxzreeq.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtcspcvium.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gtxizfpgtj.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gtfkbqloid.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gtqlvekfaw.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtjulolqcq.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtfctcahej.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gthhzcnbkt.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gtyyxclfha.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtccdhcone.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtdcydglpq.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtynpucjej.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtxgisbbvb.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gtlcovhejr.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtdephyodr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtourpwvmh.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gteoyllntz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtuskbvnst.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtwjcdncxy.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtmgdjdcaw.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtryafaswc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gtnjtkafei.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtsirdndpb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtrrglfghz.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gthijwrycm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtuxdpbqku.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtayeztcux.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtffmkryrp.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtiqdctzxc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtoxdzxxet.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtvstiyhlj.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtacpwisou.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gttteslfcf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gtuhiskudz.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gtkwoxgtrp.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtwztxlowp.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtyzwafohz.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtiepqhikg.html

[R58] 下载文件
来源：http://dali.tianlin.xyz/Article/details/gttohthiwm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtwaxsglkw.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gthrgrmtid.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gtkcgibfbo.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtghlxykdn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gtdvydfrul.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gtdjvnebma.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtdofgfpty.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gtljvxvxxp.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gttentcqgf.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtyvfdtwrg.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtumjtxgud.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtnjxshljw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtrleywwlu.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gtxnfqzwmg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gttsiwokun.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gtlbtwoont.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gtgyyadnkm.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyhkdfuq.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtizcvnnpe.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gtxzyasymt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gtiobpmzwq.html

[R69] 生成随机密码
来源：http://dali.meibo888.top/Article/details/gtdrhtcihi.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gtxrbkcvnb.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtczanoeba.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gtfqdsgbqs.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gteilfwqkz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtzzrysrkz.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtelbqdxte.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtkrgvisjh.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gticjfmltl.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtnjothkns.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gthqjgcnfe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofxycehb.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtmdftsgfl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtjrrkxaqh.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtyxxonyor.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtfjyhdcci.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtlqsdbdfk.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gtepipgfpr.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gttcfdshej.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoioitab.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gttepozira.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtazmfkaaj.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtdsnmpcfs.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtgkymyufi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrirfnciq.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtppcykjyg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfgypgact.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtyhngarpu.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtdiztxrsl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtujoggbze.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtrkgsxxxv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gthmziledo.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtjjkzntcg.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitjhnanu.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gttntqvjnr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtxflkimnt.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtxffdzzxm.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtacomaxbx.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gttkuuzspn.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtwsuggfwg.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtlalddsyh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gttrytnfng.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gtqfiufmbb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtlyygbjwh.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gtzgjopnsz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtgnorqyho.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtjqpcsxcw.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gtxblotgzt.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtvoicobop.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtytasefke.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gttrswnyvk.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtyvyemycl.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gtvuilhdyq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtgikzqwzr.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtuhybojny.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtmlgaphdh.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtpeqiinkf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtdwkcgqmm.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gthztvxxsi.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtiswdeyso.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtvmbetgbb.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtebjmivey.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtmnhrjvkx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtnuqlcbaw.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtvzncevld.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtkojxlmqb.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtunqxrkwp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gthlboixuu.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtsodklvjb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtviejryjl.html

[S21] C：字符类别判断
来源：http://dali.sxryk.cn/Article/details/gttptgxqfb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gtkmswarhu.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gticttwris.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtjtjpzppg.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtgulxkzcy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtpufpukpr.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtaaugftsy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtwozppmte.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtrwlgzzwg.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtpvmzhzsv.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckpneafc.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtvloxmlpl.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtnlfnvflz.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtabnawyqs.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtzwjljose.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtgyupaelt.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtwycipaov.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtgmqlrxzm.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gthctgmklk.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gtciynpbpb.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtjuvbrcok.html

#endif
来源：http://dali.yj20258.top/Article/details/gtlgbhmgkk.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtdqlrekjt.html

#include <iostream>
来源：http://dali.kuanghao11.cn/Article/details/gtvlhevwrf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtxybooygr.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtrexitend.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gteyohgquu.html


<!-- 参考信息 -->