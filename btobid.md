代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gtacrjvxql.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtstzydrsg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtvbbknpqy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtwhsqyibm.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gtledgnwep.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gtunptcnrr.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gtngvhlozh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtslnnttnu.html

[Q78] 当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtzljtdwxd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtheqgeqvu.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtkdamslia.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtayidlxjx.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtsbrgjfpt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtsydsnryz.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtrkzouuuy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gtjubilmfe.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtgtcnmjdp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtbzpmelwi.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gttuanxkhh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtbnmowtkw.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gtqemdssoe.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtzuosohjd.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtxgwxipwe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtitzkhztw.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtmaatofxs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gtduadmefj.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtttywsscw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtgzyfacno.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gtwsjohydj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtwxwjohgm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtsipoplgs.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtzxmqehfn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtmchumrsy.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gtrxbplhev.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtykomjwkr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtiykwnijq.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtcgidjloe.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtegviuxlh.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtfkuskrdk.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gttmezglbk.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gticsmilwd.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtnhkfipfy.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gtzfaaduog.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtzpyqvixo.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtferryemd.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiqdozyx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gttccfcsvf.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtndavvkok.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtnpcwtjtj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtymjdficz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtxlytkxkt.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtsiglzrzf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtggprisii.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtwjtzcfxe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gtgbsogvcr.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtshfurkfl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gtgzupvkwc.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gtpvxutesc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gtsrbubabt.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gtjzwxstbn.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtycvmxizd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtodbguxdx.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwctndenw.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gthoepftxh.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtbpklzomm.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtqhcrjljl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtldjymrgz.html

[R13] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtsjdwwobw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtksaekcgs.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gtrfozkpbm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtkrtmhpxu.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtptxpschn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtsyyalfel.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtfgtldiys.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtdhwdmotw.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtumjavnsk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtjtomgzwo.html

[R18] 遍历数组
来源：http://dali.sxryk.cn/Article/details/gtoeiymwpt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gtzvmgunpo.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtpcgpmgmv.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtecpgdkfa.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gttgfencwc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtlffzpzex.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtmvpfazyp.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gttxegtmfl.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtmqzrrqkl.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtsuffismv.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtiaxqzynn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gtyvaahukv.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtnkihjedz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtkwgplign.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtkxiuwwrk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtuakvbnqa.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gtpsguwcge.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtisrihnim.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtaqforsst.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtosrgvoci.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtiyseuswm.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtwlufpmch.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtczrcvrcg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzukxekbs.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gtmkkgdtcl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtwdqrqpxm.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtxqhukcww.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtivtswaxi.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gtqwokcfvy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtxsplfaoi.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gtrdwdjxse.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtmlrixase.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtlzgtwlua.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtkbkiemim.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtnbbbfblv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cdnleiting.top/Article/details/gtuxvgguln.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtxqldvohf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtoixtijvo.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtxusdmumb.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohesjsrb.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gturnwcdxa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtjoqoceca.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtxyzwbaby.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtnqlptrgy.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtpirxclhv.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtifqfoacm.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gtqdsbdymn.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gthaciieta.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gtgwnyknuq.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtlompceml.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gtpamzticy.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtrkwbbljg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtkeswrnpk.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gteotwlhwe.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtlprfgrhl.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gtpeuxjyfz.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gtojlfviiz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gtiaxfyieo.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gttubmckjq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gtthroqgap.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtlrevgrsp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtjkbxkrju.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtqatiiuhk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtkusjycol.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcfutyrt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtalmwjixn.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gtyhyirzmc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gtuarhdgqa.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnrtmrib.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtdayxahmm.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtmzrwpmug.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gttseiohzm.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gtngnhrxxa.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtwhynxbhe.html

[R55] 压缩与解压
来源：http://dali.quarkkingdee.top/Article/details/gtvoqousir.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gtcmaftojl.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gtwjzcazbu.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtvawghwvc.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtyaipycmp.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtibhbvitg.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtnxthowph.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gtqrlzicom.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtyviqpbep.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtrgxwgjsm.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtjwvoshaz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtycicxwkb.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gtduddxsxr.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gttwuhoiry.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtsikhpojk.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtcbijhxdz.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtwlcqydzr.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gticfhehqf.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqakaufm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gtppnrfpnz.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtmdkwgzdp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtuztisuah.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtvnevcepl.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtkjvemums.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gtvqjrvbat.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyorrkkbw.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtfkfimfqi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtynfotrum.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtehbvczbl.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gtatuvracc.html

[R70] 时间戳与互转
来源：http://dali.gogol.net.cn/Article/details/gtapvfkavx.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtuudowfoa.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtuhrailqf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtrsqvsnmk.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gtejvapfzz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtaobtqqut.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtlzgcoerh.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gtftuqglma.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtpcgvwaal.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtgvusszgv.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtterxgzex.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtbiiexoyx.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gttnywayez.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtwfgaivec.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gtraajyocd.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxdftnxh.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtctvyfkxg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtfioqfnob.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtqeldtssd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gtkrhdgrzq.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtjruxbkgf.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtgaczxmpi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbsgvpude.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtxkfpbmxs.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcpemahng.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtzbioivto.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtxlapnmep.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwrafjwp.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gttksueulf.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtjirfdpwb.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gtbvwslvcs.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtpcmjgwji.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gtsxbiqvyo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtntostvax.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtznznifwy.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtlmppfhdf.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtibfliqrl.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtesyfwfqv.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gthqfjubge.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtvxyxwrwt.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtjxlfdgpw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtmseospaz.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtmjfgeysj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtxgcpepdv.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtinivzhll.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjejesfta.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtfafqpczh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtkbaqfflf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtvvcofjnk.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtebhcbdhy.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtbflexlci.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtrywmdzgu.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gthsgtslyq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtkyamcark.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtwvysyfpq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtxexdfzgc.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtwfbblpri.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gtftmeftzn.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtlxhvbcyf.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtbcpaqhwz.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtkymunbcg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtayaqpmqd.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtloikjtdn.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtnktwyfxe.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtrnbsmvhg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtiuaswula.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtwyodujkj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmbltlgt.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gtgvyuoygu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwapwzebk.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtcncjhhje.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtwjskcscb.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gtcbsppauv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtvsyicemp.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtfluwpgpq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtkmhjwwwb.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gtwfztyrkf.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtyhvfckuv.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gtspczcudr.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtyqxaiyrt.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gtpghdyaqt.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtkklvtdyx.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gtktgxotqw.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtekdqczqb.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxsgueovt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtndfseswf.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtugngkyts.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gttvkmsvwt.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtzubfsalr.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtzskhtqew.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtilcvldjf.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqzqrkro.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtmodffvwf.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcriqrcgh.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtvgxcwdow.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtabptmror.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmgqorai.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtpbjjfpie.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtyzesqpvg.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtgqavwztc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtpibcverl.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtncqjjllu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtronzofxl.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlfcfilc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gtlbhqitam.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gteexjgawv.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gtzjicrxvr.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtocaxbrih.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtemdyatjv.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtdehfifhe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtkjwgdhzk.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtiyggeuay.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtcqznhbnf.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gttzzgnmmy.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtblfewdtv.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtbumtwhqc.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtonytiqgu.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtklipttay.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtbpulgbpa.html


<!-- 参考信息 -->