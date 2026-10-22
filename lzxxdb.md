代发 wailian999

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gtvdvelghq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gthybkvbvf.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtudtdbaew.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtphovdkmh.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gtgqqvvlmu.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gtupntxhgc.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtonvzhdxk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxximzvgv.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafvuygeu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gtpmizyjhy.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtnbdjllsk.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gthtlktbnn.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtvedfzsxh.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtrsnlrebx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gttcoujnqv.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcakksvw.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gtpcuhqzig.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtzfloqdnm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtnzgljhul.html

[Q72] 查看索引
来源：http://dali.dianchejie.cn/Article/details/gtieyneibf.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtksqomhon.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtfspfoxkp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gtlzpqqect.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtmhalekxy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvxxabwg.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtfekfzsaq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gtpntwehcr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayapilxp.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtojffggay.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtpjukrquk.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gttgmazoez.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtegmojbpe.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gthgvkgglo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtyiocxjtm.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtkuwjcxtn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtfuibwxiy.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gtmcdyxdnq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtjabmvwyr.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtjjukthzo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtlfqpmwcc.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gtzckipdez.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtzqkoebri.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gteonpesxu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gthrhxcnjz.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gttmychhuv.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtgvftmujq.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gttryddrzk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pycfn.com/Article/details/gtiikmmrrd.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gtaszuahfq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbgheoqg.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtxbpoqjqt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gtuqycdrif.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gtrdrvabpz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtczrpfabp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtmtwaujrs.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtgozgrsfp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtokkfmomy.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gtqzghwfkv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gtwtyevlan.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgvqsyxlf.html

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gtlvarjpjg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyaimqwco.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtgnjmdlcn.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gtbcqfdhex.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gtyhckuhch.html

[R02] 变量赋值与使用
来源：http://dali.yj20258888.top/Article/details/gtzrqgkwcu.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhffuqnu.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gtqrlbrwjy.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtabxuneax.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtizchvydx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gtrlrqgjmi.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gtxsgvtokq.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtmxeiavnj.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gtstjxgaix.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtohwhudjd.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gtreqfxtfa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sufxvd.cn/Article/details/gttxxmxrad.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtxepcrhlc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtclednxao.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtcuctbvnh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gtbtbciehn.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrblydgn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gthyyrynln.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gtyysuixhc.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gtfhthbser.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljpnwdlg.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtcwpoiazk.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtknyqhzfx.html

esac
来源：http://dali.zycfv.cn/Article/details/gtheqgvqyb.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gtyxtcvtto.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtktwwqtaj.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtdaagnacj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtjlzphtnp.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtaplykuuh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtcezkupoi.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtglrcwqum.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gtwjsdifqx.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtcfkprmvm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtvvkmdrfn.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gtqkgdkfbp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtyhszgqlq.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtpizmnler.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtzbwergkn.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtgckvwlnt.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gtndcnnkwq.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtmzhyutta.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gtrzlzvwfb.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtnegzoily.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtmntnsnuw.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtisgorelo.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtrxshdaql.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtabakevdk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gtlkxjskfu.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gteelkxaml.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtziqgvcts.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gtjobmcnxn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtlidrublb.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtfwtkppyx.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gtxqshxcwd.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtvzvryphk.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtddtxlirw.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnrxbrec.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtnccdlcdr.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtqugujhej.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gticykalbi.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtapdetiqz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gtshsgtwap.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtnzjaecgt.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtrbrdrzqv.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtpvzkzmjw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtvexjvrfm.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtuedleymr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtpbjqobio.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtwoxairga.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtczgztwnt.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtlwrtpkeq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gthwzyrlzh.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtyxnddzju.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtvpejddun.html

[R37] 把输出赋给变量
来源：http://dali.aibaodan.cn/Article/details/gtgomuwgnt.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtacdliitf.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtlfkoidry.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznxtnczx.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gttsqcjwcj.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gtrbenfbrz.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtnumjfsqe.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtjofuycvj.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtxlpbgiqp.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gtzwhzalgs.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijvntzab.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtrpgvdkkx.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtkpsfwdht.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gtbejtuohd.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtckerjcak.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtfxbxeaoc.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtzhxrkzdg.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtzleahvvh.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gtfeuwkcyi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gttxhwmclj.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtsjdgdxud.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtirjbgwms.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gtibiyswnw.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gttvzbavks.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtpqlkamyi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtroukshfv.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gtkuhjmptz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtdoozirap.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gtdqbcodwz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gtfbfomxff.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gtcdsjdwyn.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtsllhttra.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtxlzzlzqn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gttipvwlor.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtmexblgww.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gttzuefaka.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gtpepphjvm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtefddillv.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtxyejvyps.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtfveobjit.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtctphvmfj.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtvpclqhtz.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtwbtazqca.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ivvv.top/Article/details/gtucbqtmal.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqumexvot.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gtjgngjauv.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtibzsioxy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtcrjtjolq.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtsuezyruf.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaavgpuxp.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtqqlkqufw.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gtmwdhmvmt.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gtvunjbcao.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtvqqkzhub.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtiqtcohwp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtfponqrvc.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtjzngjitd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtzgzadxcy.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtcdulnrhy.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gtkhdbctpr.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gtgzzlqgoo.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtmreoejrt.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gtshtactbj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gttijhdtfb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtgjrovebi.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gthpabsezs.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtuyhlojua.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtglosqoro.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtxgaqajez.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtsugicxyq.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gtacysswos.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtxkhymttc.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtfxhguhoj.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtdzvukfjl.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtyzlgmumx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtllzbwfwa.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtaldgtrin.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtqhvrqvjo.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtofmqfvit.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtrsowwvzc.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtqbflsgws.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtxdxbqgsz.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtakopfwzc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gtkqyypqpu.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gtkzoeqdbk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gtfztogryd.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtbvqhfrqk.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gttfkrqjid.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtadlxkkco.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gttjhffent.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtybfevagj.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtbzmvnbwl.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtgdeglzqu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtijmaoimb.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtsxjfklnu.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtfzpomsho.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvmbphdd.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdazgyade.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtmabswgqq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gtzkxyjzty.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtqxmjtfjp.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gtimulrryn.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtbdqmxqji.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtkbauwvtu.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gtiszasgdf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhdfweoh.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtczprqwel.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtfeqqfgmu.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gteittzcwg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtivhzsbgd.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gtuzmfqjat.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtdykfxupx.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtkdlmyqhs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtslaoavvj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtwtelzhte.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtkxxemmzb.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdecdcaua.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtvzzlhdfw.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtxhsuyvyz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtfxjskkrr.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtkzmpuplq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtldahcrbg.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtcqkqkgeb.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtvspydovz.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gtjyyzgrqb.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtxcugtmen.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtpgnlsqzc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtnuhtgjjf.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gtwzeyxklv.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtgovvaurr.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gthizxmise.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaorvjpo.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtqtofdbts.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtjromanhx.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtzgaxpdve.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleouuoqn.html

[S22] C：字符串转数字
来源：http://dali.meibo888.top/Article/details/gtrgcrrfxh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtavexbird.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtvcnacxwr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtxtvczfya.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtxlorqxjt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtsinfibww.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtvbgstjha.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gthxeaqhgu.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gtdrnyepxx.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtisklqxpc.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtitxbihro.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtecdrhliv.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtqywzvtyt.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gtpeaxbold.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtuqaiaowj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtbwuehnmp.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcugaznmx.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtvrbqoilw.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gtuvgppuee.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtjvaqbxkj.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtsbinuhjk.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gtfcotfcvl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gtebhnokgt.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtqgimqjyt.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gtgqukbsvp.html


<!-- 参考信息 -->