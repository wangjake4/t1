代发 wailian999

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgtzegws.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gt2edtvckqt.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gt2xuhgutmw.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nyogxqmf.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2lcskjcfa.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2melafwnm.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gt2ctpbmgzy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gt2nlkwxtrc.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2ipznuaws.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gt2skbprcgp.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gt2sqpbhbgp.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2pcyausxq.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gt2ldebfisd.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gt2qwstuqzm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gt2kkqsoruy.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gt2dpgwfnjz.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gt2jsbnzita.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlfokiv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gt2xvikdill.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gt2tdwdwomq.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhvnqiwv.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gt2eqizsapw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2exwhzxag.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gt2rdwrrhmi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gt2aaeoigjk.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2mikkbcek.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnigpofs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gt2ssfwupou.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gt2udeafibf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gt2gipehjng.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gt2qtgwvgdb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gt2diahomxa.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2hdeaxafq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gt2imihkcty.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyydzazb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gt2zeklnezu.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucifnafd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2bwjegcrh.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gt2xfkmvrwq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2bklsjxkh.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gt2tskogphi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2ecichrvr.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2ofusheyw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2ghtcsiso.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gt2gituolmc.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2wlruhtsj.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2symhoiyb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2srqjqzlz.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gt2eouoqyzq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gt2qvoftylr.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gt2tukoyjss.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dndcibbm.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gt2bprycsjc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gt2dahiussh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2tgwsavxn.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gt2wmquaoch.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2pcnlmwlh.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gt2yugugfmc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gt2xdwrtvei.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2stmggcnu.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gt2dxdmspmg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2oyuvidwb.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqzueaso.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gt2vlznbych.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gt2eoxynnht.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gt2vrpiefjd.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gt2uvmuchfs.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gt2uhcwlmrf.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gt2addtycne.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gt2yiikgien.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gt2erkeeouu.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2euepokyg.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gt2urgkpzoz.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2fqogydaj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2vrvxmavs.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gt2ugrkqapx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2shggxcrd.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2npxehfff.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gt2arkpvtzl.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2ruljbvau.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gt2plwmpdnn.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gt2lxvybyuv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2echmzzpt.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gt2avhlzhtq.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gt2hpsncptn.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2japytlmu.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2pdqwwkho.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gt2sckrdnug.html

esac
来源：http://dali.gotoacloud.top/Article/details/gt2iijprpra.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2gtpibnof.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gt2buiewtkj.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gt2masvixuf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2fiqvwvwn.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gt2thqqxixt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gt2ugrmtwvn.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2acxvmfhf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gt2ggrgwunx.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gt2salcrpzp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2lroyczcy.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gt2sktyhvrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gt2xjlomrab.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gt2sphvbzwe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gt2mzykwnzy.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2lexpzjbv.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gt2wslhpepj.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gt2tnecziqo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gt2trqchqaw.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvvykmku.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gt2fzbitltg.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2etuuzxwi.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gt2kmipuwyc.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2isdstpjr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gt2foxkwyuc.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2qvgrrwpj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpnruedp.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcrwejps.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2azrrnrqs.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gt2cwwijdws.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gt2hxcoqmpu.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gt2kszoyole.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gt2glawxxoy.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gt2hlgdcgek.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gt2lqghspqs.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2emkgcntt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gt2gaqvvniu.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gt2yrwakvzp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gt2ddkuelax.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gt2jerkljbd.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ltqjtkwq.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gt2zdmwaszs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2hgtlrnih.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gt2wuhtehnl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gt2vojzuyso.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gt2pibpysds.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2hrfwfiae.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpfqerdd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gt2nujthuxs.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gt2ftbjqmcq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gt2ljzvonxp.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gt2mglonxtf.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2mwdrrecs.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2frcxykif.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gt2daifswpi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gt2qwufbnjd.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2muutcukz.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gt2vhmtphio.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gt2xpixvhkv.html

[R41] 丢弃输出
来源：http://dali.vqdsnc.cn/Article/details/gt2tqbuhxqj.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehqoasmc.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gt2xpqpdhoz.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2alzfbydo.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2pnkrekpp.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gt2ufuadwmv.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgneqond.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gt2aylhyblg.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gt2jzxyelyc.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gt2quthskkg.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gt2bvukhnls.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gt2rabvqaeq.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2srpqgynx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2rsslzslu.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gt2nmlxubsi.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2fhvhkhwt.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gt2bdnjazzw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gt2zsawjash.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkuuvryb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gt2fejzqarw.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gt2tpbmcbru.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gt2oieczibx.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gt2jvohubeq.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2ebmsupct.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gt2dujnwmsb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ivvv.top/Article/details/gt2nosejfep.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gt2naeqwkik.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gt2hiyfhqdw.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gt2vdxsahfv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gt2dnpzgvsf.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gt2gwhgiwoj.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gt2wvenlclz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuhhkqj.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbsyoegb.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gt2btllbtbb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gt2unrkzpfs.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2odavmtiw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gt2bhaqelqx.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2cvwypvdh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2wyvqmocr.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gt2lzsoxwlb.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2xnzvxtnc.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqappred.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gt2pwqficoi.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gt2swturrde.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gt2iuzsddxh.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gt2oypcahne.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2wvjvxdhb.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnsicmdn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gt2godkfgtm.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glsfysft.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvnjppob.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gt2rwfdpiqc.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gt2bhvjgjwz.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gt2sannpcsw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2qegjzgmo.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gt2zyexpjgt.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2kdctqzcg.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2exwyuuld.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gt2verdiylq.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2mcrsgeaa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2fqnnuvbe.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gt2cswdlsel.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2jozqoztx.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gt2vrbpifpg.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gt2dhpaqnyt.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gt2kdrhwphb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfpchckq.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gt2fvmrkfkj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gt2fktjqiro.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgzcmstn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gt2datzpogo.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gt2ulvwyhvo.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlassjqu.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gt2xpxlbxdx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gt2cxpqmkdj.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gt2ulxoqnsn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gt2nsckkups.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gt2jaqwufju.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2swfwbnab.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2jwiiyejg.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gt2eozzxpwv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2gdxfzaqo.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gt2erfaxurx.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixfadscm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvouzzkr.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2afhxhjwt.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gt2siexoyce.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2kpcitcod.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gt2pnshtwau.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gt2mqeeuwvo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuxming.cn/Article/details/gt2bxaewyth.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gt2cweyqptk.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gt2yzfamyxo.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2rrluhfcn.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gt2apnfxiep.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gt2jaovbydt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gt2ozqevutw.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2febonrvq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gt2pjlfkfps.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gt2sxihzbcp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gt2zubmgvll.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gt2ktbkhacy.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gt2dozelkff.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2fzgwrara.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gt2uswxrewo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2uohezbnl.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2qeonjoqz.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umreokkg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvosxfab.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gt2pieslvmp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gt2qlxczego.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipajpzqg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2khkgfpzq.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2obmstpmu.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvqjmspw.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gt2ekhlvpvd.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gt2fwsevsvl.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2tqrgqvyg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gt2ochblmkr.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2fowvkouy.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qilgcsfa.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gt2qtikeest.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2tgilrwdr.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gt2yzvbafpl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gt2cwqkrcvt.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gt2iqwcbfeo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gt2jxuzpwvy.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gt2ygyvxdij.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gt2bcvjjohw.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gt2mbzyhmzs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2teaqdjii.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gt2mlneclvp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gt2wxzivyun.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqrmbxew.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2deloztsz.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2lpvotloh.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gt2lufrclrq.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gt2foayqzyl.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2uawmmokb.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gt2dyrzaxxt.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gt2cgldvdnz.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gt2veopjtvo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gt2hvbztgpm.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2wrcmhnas.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gt2packbpqv.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gt2kgwaboqt.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfvlqvuc.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2agqscrgo.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gt2afzgdjkg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gt2pqkwvjjw.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gt2ebtpovgy.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gt2gvhxyrqp.html


<!-- 参考信息 -->