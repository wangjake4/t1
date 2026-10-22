代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gt2pqgvycla.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2ytelhlhe.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2deutkpwb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gt2ydyxfyii.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gt2bbpjujey.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtjouewx.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2lgkofqyw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gt2ingeqlmc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gt2qbzpdtjf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gt2anufbmcg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2rbbgtkgq.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gt2iotknfuk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gt2aknlymdy.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gt2rwbonspl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gt2vqazrtyt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ybipulsy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qckjxvgo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2otrozkqb.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gt2iknuevub.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoblamto.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gt2conxiylx.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gt2iengrxcd.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gt2fswvuqbz.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gt2ayidjrna.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gt2iodngefh.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gt2tlctfqbh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rittyxkg.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcaerdoz.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gt2gumiytlb.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gt2boollgom.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2vwayeypd.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gt2tcgekbjd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsjsgcov.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2riuzceja.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gt2unwafazp.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gt2xlmduwtg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2mekopszm.html

[R10] 正则匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2shuzjgej.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gt2sdqerkof.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gt2zgotxkti.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gt2lzlccozx.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gt2utdvtjrv.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gt2wlerjkqh.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2brizrpfz.html

esac
来源：http://dali.sxryk.cn/Article/details/gt2djjuxjyj.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gt2usydauae.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gt2rigffvmm.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gt2lqszpcmb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdgyfyat.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gt2gczmzjpv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ochgzozz.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlrjwrao.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gt2bvddeprv.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2tntowuct.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gt2kilazkix.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gt2tiolwbxj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gt2hvgbkwkh.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gt2fgpnplyu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttfmryzh.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2cuapaqws.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gt2kvqybiiq.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gt2bgbzfdrx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gt2nrbfrbfs.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2ppsqzpuu.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbogsena.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2fogrjcqh.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gt2flsuteoq.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2dhpbqqkh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gt2zmcasyvy.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2rpyymgfe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gt2oduiuycq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gt2npwrwknw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gt2nbcqkcvo.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqimbufk.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gt2pucnddcd.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gt2ofeloove.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gt2spdlmyqo.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfqoctpd.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxirfgid.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2raeqoupu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gt2xzpjnddl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ontbcxwu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gt2ddfledrs.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gt2mntcyfbg.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gt2qtieyzyt.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gt2johbqzsz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gt2hzzupcld.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gt2yuhskwyx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gt2ldsluwvf.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gt2lpvoudgs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2cvpphyvn.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gt2tbvdegyq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gt2yflkdoyj.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gt2bahhtcdy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gt2hkrtsbiy.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcxpvnms.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gt2wpucpzra.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gt2aqhfpicj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gt2vicumemn.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gt2vyxwqbak.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2qjtaeokb.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gt2tmusqpvv.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzytonpc.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2odjlvkzz.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gt2hbabcpuz.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gt2ffdhkkbq.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2yofjokug.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2hodtveuf.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gt2uyqmcngh.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntjacufn.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2yzhlnmlh.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2mmwfftsw.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gt2jvvdzypo.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gt2hhssbrkq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibrwgxsy.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gt2cvqbeiwh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2liiwukri.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2okusjdnw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfdyhinv.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gt2caopymrc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gt2ntcznzpz.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gt2lxgoyehv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2knjclvek.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gt2koavmynr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2xbzmpkzd.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gt2igdlexoa.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2hvhbieet.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gt2fzjlfgyn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gt2juitmqft.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gt2qhotblyd.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gt2njfolill.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gt2gtlgempz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gt2gaclxwek.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2urzwlwni.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gt2heqxrggm.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gt2bwbwjgif.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gt2qchozhql.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2sgewnmfo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gt2ndimxfxi.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2uyyltmyj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gt2dvwdckwu.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gt2nsfbifft.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gt2sxkvelku.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gt2wspvrlsp.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gt2jryvhxav.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gt2whfeusus.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gt2gzulbbpj.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gt2icuueomr.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wskkeddj.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gt2okyfizrg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtstrwj.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gt2egybzniw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbidxsm.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gt2lrnyakao.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gt2mtdkvasp.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gt2grqfrcmy.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gt2utletqpz.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gt2nqhndawl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gt2wekecdiv.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gt2ryaflfhj.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gt2zbuumydl.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gt2uupdiuwt.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gt2xjvhlyej.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gt2jqymuzyp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gt2wklxenuj.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gt2goqfgybs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isrvvftu.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wiscklgu.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2ovzihvoc.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gt2bxgexqkq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gt2mbcbokjo.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gt2unkssmwh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gt2pcscvzwc.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gt2zkolhbjx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdfmuhvi.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2oappmpay.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gt2zxacwbxq.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2ucykzfgl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2tizlgpay.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imqslrae.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gt2vaebhmdn.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gt2awotvvqg.html

time ./run.sh
来源：http://dali.cdnleiting.top/Article/details/gt2lirfuyiw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpnznmvh.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gt2ezbzufex.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2gbrsbomd.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2hlkzsiju.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2thbpbjtq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gt2owbhhvhy.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gt2yjtbqagy.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gt2yrqoczze.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gt2qufrtnnj.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtnkjkxl.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gt2gesznpql.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsbeewwj.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2ityupbyw.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gt2stdhqgya.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gt2qhvxhkdr.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gt2xcgidlec.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gt2yveflnvj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gt2qjxyfumi.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gt2eokcrsqx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gt2irdfxhqi.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gt2abkwkzxl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2ydpwvhto.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gt2cgdopstf.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gt2kfauiknf.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2reaysmzp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gt2elwiwkvk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gt2qpwlqwmh.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxjrupts.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2vejlxnhn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gt2gdvhhfac.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gt2qzhksjwh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gt2wlfxsenf.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2udmucahe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cividzad.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gt2cepbysvq.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gt2nsjzxlrw.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gt2qxhhvvmj.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsajuysa.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2gbvnodbc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gt2slnycwmp.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2bbbncrrh.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gt2levhyzxj.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gt2svvrdcmi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2stpnrjiu.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gt2hcjgrito.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2lxbracxr.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2afastcrc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqaayesn.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gt2opcaipzp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gt2xxykkmqz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2flmeseiz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbvhkgee.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gt2miqwicta.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gt2dijpahjo.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2eyamcsfw.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gt2klpvrhdc.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gt2ytbzmrjg.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gt2afmvkxxo.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gt2ifrzyhzu.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2ritzbwyn.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gt2onhxsblr.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gt2usowedeu.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gt2jrgsfhzu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gt2fenswrzj.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gt2egjfmrzg.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gt2yxdkcwqs.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2ecfkqaul.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gt2kaschnro.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2oawlcpbu.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdwibvsk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gt2pjeopdqy.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxqcjqmj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hprbmkqk.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwxjrawy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2gogghzlb.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gt2bmuzizjv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2itkglmgd.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gt2xhyicwnf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2cheflfin.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gt2wlbwswqj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2tkmutrub.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gt2xooljiiy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gt2kdfsjoxh.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gt2tcgfhzzj.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2setcmobl.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obbsrgyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gt2xyowrbon.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trxuhoeq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gt2xphyvqyq.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2pyeetzbz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gt2trzallsg.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gt2xggivkrm.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gt2otgoxqzb.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gt2dmuabrxe.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2wxldncrw.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gt2tdolalgh.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gt2mnybszhe.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcwzqvys.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gt2bzedaqvj.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmpbxayw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yrqmwvek.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2opvrbjis.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypqklhyb.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2vvrwhmfi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gt2ddrrfsnw.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gt2mtlmpsdn.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2pyzymonm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlzsujgj.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gt2pjhsukrn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2uuqykjgt.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2vctxkfvy.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnimrrgq.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gt2uevxjznk.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gt2guqwqaga.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gt2xybbhpcg.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2rytczxgl.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gt2nmhdpwue.html


<!-- 参考信息 -->