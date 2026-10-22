代发 wailian999

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gt2ystluozw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zywzeufc.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2paoveicv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2qstesqmd.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gt2uezmhvux.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2erwsukbe.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2scroxsde.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2ddgdeogg.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgwbwtar.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2gfhlvwjd.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gt2luypdlgq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gt2gtrddxlz.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gt2jwnsqieb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gt2zsxzcxwb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqahxjtw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gt2hcctxkya.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gt2jxsgjonh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gt2fstjryoq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gt2upwecbkn.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2uulovdxj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gt2wdbbqppl.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gt2jnynsmrx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gt2nfqxrwqq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2uzlqscsi.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gt2gxnohzsf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2mxmafobz.html

[R01] shebang 与严格模式
来源：http://dali.shuidangran.top/Article/details/gt2ikesjkms.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gt2lfnehyyw.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxdtfelt.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gt2pphgbuwk.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gt2pdbyyaip.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqcwrvqq.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gt2lzyramck.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gt2pqrjnfmx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gt2rucwivsa.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gt2jcvmhwtt.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gt2mmpbqffv.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gt2ivvqehka.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbnyrqke.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fubjqqdn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gt2hvjkylkq.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gt2awvkrsnb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2pbhtucci.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2zklxqrxn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gt2ssarcrad.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gt2yjcxzuyp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2fhogknsw.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gt2tqgjcxjd.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gt2kldeisnn.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gt2vnzvzbtl.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2ktrevrwm.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2eimoplly.html

esac
来源：http://dali.xuanzx.com/Article/details/gt2dwdiuwky.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gt2hqagbuqh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gt2rfcctwyh.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2dcpqshsx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2pzsxdmvm.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkxcwmav.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2iopaktzx.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2qjskaqgp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyzhsfl.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2nzkmyrmi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmwtinyq.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gt2bwgjuxmp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gt2rrqhvjqa.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gt2ljymexnh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gt2qwavkxav.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2jgwvsasd.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gt2rwdeyaep.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isfsqott.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gt2pjchkmtm.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gt2ogpderfh.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gt2epiiymnq.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gt2bqsncknc.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gt2wcabdarw.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2xlucrbvd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmtiqopw.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gt2trjjiojx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gt2hapkdbzc.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gt2lqcabbdw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gt2prhpxygm.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gt2blanvtde.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfmyzlof.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gt2mttvdsnf.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gt2vpdsznnw.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gt2ofvzmhgt.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gt2ddiyeoxm.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gt2wtrmrhyi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gt2oosgccym.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2lgqlesda.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gt2htdhrszs.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phqicuur.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gt2byupecbc.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gt2euhfimhz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2htphyzab.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gt2qwhbbqpw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gt2ydwvxrbh.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gt2srkockxs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqjzygu.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gt2xsfpayot.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gt2gjpkjrqa.html

[R36] 并发执行多个任务
来源：http://dali.cheryme.top/Article/details/gt2oerjjcmt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gt2hduyykqb.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gt2mikrpvpm.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gt2nqlhqmcn.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gt2ajfvgapp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gt2cuxfunlm.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gt2knznquzq.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2iosnnpgg.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gt2qojanita.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gt2ffbvcgty.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2eugwhnpv.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gt2tdxmafoh.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gt2cecfqnxf.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2zhexitgj.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gt2zfbmcgkv.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gt2bdrftbeq.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gt2sluuhdsq.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2dzjmtwip.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gt2hsfigfkv.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gt2ovsqzrjs.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gt2zmhfktla.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbqfbbpk.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gt2ymvinyeh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gt2itoqyznn.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gt2vlszbvgl.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ydbbjwvj.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gt2yljbkqsl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2vsumlkbf.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gt2lionyouf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkroybsh.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzgeukjb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2ttthmukq.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gt2jptsfanb.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2jguccdmi.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srdqlajm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gt2dgjetuak.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gt2vxmftztw.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gt2ovilsstu.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2iekpkcgx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gt2mkthjldl.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2xpdhqtxi.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gt2jjfymzlw.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gt2wxbtnoaw.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gt2antgzlll.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gt2ipymwumu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gt2ggaapzdm.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iojlvnqe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gt2uuhoblfx.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsbfxapp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gt2axhxdrig.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gt2dazeldro.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gt2mpdgwnvv.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gt2bknytehl.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2xdknuyln.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gt2manvhzwc.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gt2lbgocbfc.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gt2euppetwn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gt2zobqxsbt.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gt2spdsggjg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gt2akrpbukx.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gt2nmeojexz.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbrvzqpg.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gt2tmodqtgo.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2njrkohni.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gt2kfbqsrcb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2txyxlooj.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gt2fsukxnlo.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehmeiliq.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gt2msxhlzzf.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnwjgpxl.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2vspqjukx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gt2qbtskkhw.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gt2ckbrzzcd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gt2ujebmzkf.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gt2rscvscxh.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gt2grtqakco.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gt2sayysrao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gt2atvspjvk.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gt2uayijwog.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gt2vtbzjcyb.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2zckteler.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gt2pkdybzcd.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcvsduvz.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gt2zuqksvjp.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gt2vvqgutgk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gt2aqhpziuo.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gt2ujymhuvb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gt2wwlfoyfo.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gt2uxixyzvm.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gt2tcpiihau.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2lknequxd.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gt2wjmwmber.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2fqfejofn.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2dtxwhard.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gt2sqjawuku.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gt2nysktbqn.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gt2pitusvxz.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncggmnut.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gt2anklccvq.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gt2msihkbiv.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gt2gvgjvvcl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2ybwactic.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2kkvhczsj.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuhpzjmu.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2xidullfy.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejmvfvzv.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2dekpozyf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gt2zmkosydk.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gt2mrlmjsns.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gt2zbbgdkut.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2epcirprd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gt2hgilnqfz.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gt2lszmpeeo.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qptrwkvt.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2szesakks.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gt2tcodcvwe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2dzrakptj.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gt2plseysuf.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gt2mqwatvjr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2gzndiuqo.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gt2izyobrco.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gt2ffdrndlo.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2mnoroufi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gt2rociwpew.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gt2wytzurcb.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gt2yqgexqxi.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gt2jdqjisjr.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gt2eafrqipb.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2bqfxqczt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gt2xocmnsvd.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2ywubtzec.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gt2vrqntnro.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gt2xhlzhuwi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2tlqairup.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gt2iemsdfei.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2wsbatmcx.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gt2dqtghkzs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gt2fwcdmqxh.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gt2hcdbvnri.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2iejkgkao.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yadlzspf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gt2ingnwwdo.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gt2kldissir.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gt2xnjcglrn.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2qtirkgqk.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gt2vofsrgte.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gt2bbeowjth.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gt2styqdfkc.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2smciczex.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2ptexhsbs.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2euhjoccc.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gt2wgqcvbhq.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gt2nzzanlhb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gt2cthmeuaa.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gt2mntxftbe.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdneypqg.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gt2hjwgwzze.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gt2fbcfrwyz.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2pzrkolby.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gt2whsgwuqd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gt2priyrjav.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gt2nepgsqhg.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gt2soyqmkzs.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gt2shqoeecc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gt2mafyuokh.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2kgvxqijb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gt2oifaxbas.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxwbghtr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2xnatzong.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gt2jpahmxtx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2sofilxmx.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxgrlmzb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jouhbxnf.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gt2ggasuqtm.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gt2divvgstk.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gt2tvjqcada.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gt2gwshiepv.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gt2iqpzoexa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gt2ykisbebe.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2gsbylrst.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gt2ykhkhwdf.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gt2igykigld.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gt2asqdpfna.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2tvrduooy.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gt2aemgxjmo.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gt2qozkzohs.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gt2pwtarsac.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gt2jqexqrvd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gt2qcvnrxsu.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2zloygibh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcsjlnyd.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gt2eherscpa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kfnsqfer.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2lzhhceqg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gt2giparhko.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2sdzrcfpf.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gt2pzdwmbii.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gt2quujxktt.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2adsizkbs.html


<!-- 参考信息 -->