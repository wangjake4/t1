代发 wailian999

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gt2qxablhmr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gt2itpvptds.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gt2ojwitqzq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gt2vopulueu.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2fkiidpxo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gt2uxdvzghd.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptndupap.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gt2pvsvqtpu.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gt2fusttwfk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2bmdlqwel.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2anfditpm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2mlsltrsj.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gt2lnnfltpz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2hxjsnulb.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gt2uogcexnn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2ohvuqwgn.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gt2fejnjshz.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2pihupdqs.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsbttymr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wiktxhej.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gt2slspuctd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gt2twkaanin.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gt2csyfgjes.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gt2paufapji.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gt2vxdpvllh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dashuyun.cn/Article/details/gt2sdonrugf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2wkjubvbm.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2zgrlrhnh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gt2oerdnfnj.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gt2icpmkqxv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gt2llgcqppm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2komjbzcx.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkmizlwv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2svralblq.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylyczsyj.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gt2cnmtkfbg.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gt2anneqwvn.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gt2fpfximce.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gt2ianhwxxr.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gt2njwkwbni.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gt2zjxmqpxn.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gt2bjqstzxw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gt2liouopxo.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gt2vbzuujnu.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gt2tqcxsqlf.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gt2rtoarhsc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gt2hsvtbwir.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gt2rgkrudok.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2eststctb.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2qfeozzoy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2rrxbghhd.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwyjygqt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gt2fmcatjce.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gt2hwwcnmpf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2geawdxpq.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gt2wxuhlsqs.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gt2lbuglyfv.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2tythbwwl.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gt2ethuhjfz.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gt2injakrkl.html

esac
来源：http://dali.redwolf501.top/Article/details/gt2qwmqmasg.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gt2fgcgrnbk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxrplapz.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gt2hyihwblp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlneehzu.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gt2nxgiwvrk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2nnpqsall.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2qqihaaoi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2biinmpmy.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gt2hzqakjdu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2vvcnisnm.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gt2avlmufnk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gt2lmgpvwim.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gt2hurbulni.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2sumlkixi.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2nrksfkox.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2klfxfnuf.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gt2dazoucis.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2pebxfdfq.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2ksruvgij.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gt2vwweixwe.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2eyfmfpks.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gt2qqkyaeho.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2burumwvs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gt2nacljmsg.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2gtqoviyz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gt2htwcjrsi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gt2jiistzqz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gt2wssgniza.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gt2hmveczrp.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gt2xnxhhqjd.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gt2wsekpdut.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gt2pnhesgyo.html

[R28] 浮点运算
来源：http://dali.hammf.cn/Article/details/gt2xpkglzja.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gt2ihwulmuu.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2jwxksfnq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gt2zyzbdljx.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2zafcmzvm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gt2lbwmiigr.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gt2qownefli.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gt2qbplbmvh.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gt2tdjgwtlp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2aeyhgfjk.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gt2ktxpffrv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2itvqlsze.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gt2cipjsboi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2tqlzhfxv.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2ujkecynh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gt2bdvzkrwv.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gt2meukyfud.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gt2ltuiadfz.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gt2dmwinpoq.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gt2gvjvjabr.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gt2zxdmdpae.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gt2ixtpehmc.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gt2yxnyzebb.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2pvsjmpsg.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gt2empghuep.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gt2nufjzzve.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gt2qkheosax.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gt2hrcyvpun.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2xtanniqq.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2kmtoijej.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gt2dmrdtnxr.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gt2yphellzz.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gt2dcahebrr.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gt2plkjvbny.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gt2xpbnzjln.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gt2dctepcwp.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gt2ynorrqta.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gt2imeedttv.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2jskuwraj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2qqxgcovh.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2swdzkjgy.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjjjlucy.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gt2rtitmyqt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gt2rxvtapbd.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2hyphwppn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2phkaybic.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gt2umkgoqla.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gt2nrnxoowb.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gt2vfeatsiv.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gt2zvaikhvs.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gt2alcczbdv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gt2ennxmigv.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffppdxor.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gt2eguickat.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gt2euejcxvf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gt2clcckvts.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gt2qesucwuj.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gt2ympfxiat.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2qblrxdhf.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gt2lqkjqymq.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gt2kcpdgcva.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gt2qyvulbmo.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2vhgogefc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gt2mbasldtx.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2fohuvapx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gt2hhwjstxg.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gt2wjafxcle.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gt2ozqpieuu.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gt2htgkhohl.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gt2ymdwpmkz.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfodfiij.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfrvismk.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gt2pmodrmoy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gt2nzltblcn.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gt2bgfkbxzv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gt2sgsnhcuy.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gt2cbhyhlio.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gt2jsplbnzq.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2ecdwlvty.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gt2htpgcrcx.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gt2vrxqnncs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gt2lmxkxczu.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gt2jymsiphr.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gt2nmbgenrl.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gt2rpagvwso.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gt2jwqqxfgt.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2wvbxqzkm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gt2arscjbrm.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gt2gabqzofg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2sbbdbuhb.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gt2rmpmqfrt.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gt2fptjgygy.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gt2lwyejgcn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gt2tvsgpiyv.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2uhpgnelo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpykzzij.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gt2nnzmyrrv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2fpyiavwh.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gt2euyrziyo.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gt2kzmaljuk.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gt2rwqbgxii.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gt2nidrmngz.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gt2tjjmgzxc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gt2zjedzpyd.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvkbktct.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdiybopl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2asgpmbgl.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2bvhemvtu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2rftnfrzv.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2uujyxymb.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgjrcfji.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gt2bvveqekc.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2enfkwxjp.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gt2mkayvqix.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gt2fnbxghve.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gt2bsaofyip.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gt2zirxloyy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gt2lwqrebhz.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkhxeuxx.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gt2tmsdfops.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flwkoeoa.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gt2ataukvqr.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gt2qplfjeyq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfkyauoh.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gt2nnrjtgfw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gt2wszdovzv.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gt2ebdufzcz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gt2bfprrplc.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gt2cfqyodmy.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gt2ntgxbbpx.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2bmoforkt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gt2tcsxsvij.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gt2zijtamhn.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2akseaqkh.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gt2pzjqbhhr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2wgwruuqc.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gt2yrpvwljd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gt2acabijbk.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2iphluupi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gt2izslmfwc.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gt2hydfxboi.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2blirxhmj.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgrlakcc.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gt2bmdxhgok.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2dkqjxdgt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gt2hdgfphkl.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgoldclg.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gt2drapzqeo.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gt2emhiruou.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2erwbjyxo.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gt2bbvblqwm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gt2majjfnxl.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2uvbdodqp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gt2zpdbypof.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvjcdjkc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gt2jpsvlxrc.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gt2byhnxqbm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gt2asmyezil.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gt2qxybigcy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gt2ebbbfswr.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcizjxqr.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gt2xxvwhxlm.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gt2sphpsjjx.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gt2qtmgddbx.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2jpsbpmhi.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnjwasrp.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gt2mkooxpwy.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gt2lmeydvyj.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gt2flvgmene.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gt2zvpzneah.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gt2iauxsfvb.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gt2vfpwaurg.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svjyvxan.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2lzrssvrb.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2kjilrpqd.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcbaxxmc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gt2qvwmksaf.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gt2rjisyabx.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttdtoyxv.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gt2dnrvfqnr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gt2prdcnwlj.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gt2xapbpnnp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.svipenyu.cn/Article/details/gt2ivcdhflr.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gt2zngqpmyx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2puodzbkp.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gt2fuhdsjkp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2yqwqqooe.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gt2bkyspzsd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2vkeoosua.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gt2nvlemvup.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbiesfbe.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2vvytuyay.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gt2jefjefrv.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2ewohaysz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gt2qtorirjk.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gt2ydjlrmdo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2wtgzalxb.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gt2lndmgwor.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gt2ufkrjasi.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gt2rpeqruaw.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gt2uklxtmam.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbekjqwz.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gt2nlyorilr.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gt2zaarpovi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gt2jkhrnsqy.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2tzctekoz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gt2xxkexeft.html


<!-- 参考信息 -->