代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gt2syqetdeg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2vbhzvowl.html

[Q85] 数值取整
来源：http://dali.mhx1999.top/Article/details/gt2srzcjfft.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfszyevk.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuehmmvf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gt2mmpvzqrs.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrmceejg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gt2gxadixrh.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gt2cpotricj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gt2edlqatei.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gt2ctzinwwb.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2xerieelx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gt2thaeqsax.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2mcwvutlv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gt2yualwzmu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2phosriax.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2smpdqnxc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynjtomjo.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gt2fpuwtnyg.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gt2nzkqnmdg.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gt2fkplkbjd.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gt2rjqusspj.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gt2vuakredh.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gt2qduyampo.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gt2ixptjfjg.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gt2mpbwwubv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdfcqsvx.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gt2adklcvvg.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gt2cvytyozh.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gt2xxxoayuy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gt2wolyzztb.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gt2asijwipz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2vngbdldt.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2iebxxikd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gt2atgbtqte.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2potrqurk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gt2seuprlpc.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfxvyjtt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2hdusxpoe.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gt2kiunzkjt.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gt2ocdgxxxq.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqbpkviz.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2wkflslof.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gt2zzhowyuv.html

esac
来源：http://dali.gotoacloud.top/Article/details/gt2dwqauwug.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gt2ddaspgku.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gt2jcmxdhcj.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2wkwkxlah.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2tfcmfycg.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gt2gbcdxsas.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gt2zypixxto.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvujtwit.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gt2vrzuvqdd.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgzcxdiz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gt2rkeymvim.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdtjwkdb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhengqikj.top/Article/details/gt2gdonoxxr.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gt2fxyftobm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gt2tsaukhsy.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2batvagks.html

echo "${#arr[@]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcyedydk.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gt2smbdygcn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gt2hoqwporb.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxqgezkc.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gt2rkskwwfs.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2xjywxhjc.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2rxczmnkx.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2feigegrl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gt2unsrmaca.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvhfkyuq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kofbvpsl.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2uexboqtw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gt2fczbtqta.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gt2rrgydjdn.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gt2qyrsfezn.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gt2lhtexcci.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gt2otdrjsrr.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2mbdojkme.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gt2jqugmaxz.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2wzzxcrct.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gt2ijbmqgwc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2erkwkdza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2slxsoanh.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2krhvdfce.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gt2oakimjlm.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gt2ctxwwktn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gt2prudthbb.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gt2qiauyvjq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gt2oypmhkyi.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gt2pmasqefu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2qcyzywkl.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gt2rmzywrzb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gt2ogoorbxy.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gt2imjsaagk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gt2hibprowo.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gt2mjgxzier.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gt2uhjgpcym.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gt2ygvkkrxd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gt2wftywzit.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gt2kqkyhgta.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2wbgytzjs.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2ziczqmno.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gt2ysheefsh.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxnzyfwe.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2wjshnpqk.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gt2rhmjaiif.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2rockudfe.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gt2sfywehnr.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gt2undkvkyd.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gt2dejluzuw.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gt2tpghwhyn.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xylrnnja.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gt2rcgkszfb.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqkvzeje.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeszcqmq.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gt2rsjazhyf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2cssptiim.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uywcbekb.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2gjwglpkl.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gt2xiaupwcj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2sxdsgieg.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gt2qwslybln.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2xguncrpf.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxapkubs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aofhesui.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2trsfsjsi.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gt2gkyrchzf.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gt2nvayyfez.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gt2exelxvst.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gt2wskgoaul.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gt2atufkoqw.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gt2yyrexqhr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gt2zywbmfmv.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2jppyfduo.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gt2ftierebd.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gt2iblqwpuv.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gt2jlrcdlkt.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2cacmvhim.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gt2irtpbqbw.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2vztadola.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gt2qfsfkcsp.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2anjxktmy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gt2auiekite.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gt2leqyfzie.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hinzgvrg.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gt2apluwheb.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gt2tnwqlskk.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gt2vbvjhocc.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdqcnzku.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gt2ieingvrr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gt2qtbujfpn.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpeeuxbd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gt2bslcbibv.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gt2vajxudua.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2lwyvezyl.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gt2zfgjkmoz.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gt2hfmkkcdp.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gt2yiggrvlv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2ftoryvlu.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gt2vianfldg.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258888.top/Article/details/gt2yttbrfhi.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2aanhqrjs.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ignlpkbc.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2tqvlsiez.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gt2xuuwtlag.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gt2zhbsptos.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2ughyvmba.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gt2iwrpoucw.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gt2fnjeaqvx.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gt2zyklidgo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2snqlssfr.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2nqffthqd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gt2kpkuvymi.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gt2olgmcusq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2zfyebsce.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gt2yukstyeq.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gt2uuiebhai.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ideuospp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gt2eyimlxti.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2tuwgfjkd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gt2upagwxxz.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gt2xhalppit.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gt2mzcfoevx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mrodsvew.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gt2mglnktxc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wirfxdph.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2ssndgasg.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gt2eiwchnql.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gt2saypsynd.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2ypdjvdjd.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gt2pszpwijx.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gt2gdrpfnic.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gt2yuudyakn.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izfbhrks.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2rbkugdff.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2mcsrnrzd.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gt2jdlmkeiy.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2tthoeytt.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gt2lknlhbmy.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gt2mixuyfcu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gt2suicliqu.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gt2hoyyerkb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzziyknw.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gt2mtklbpvc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gt2njxhkvty.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gt2fttwybyr.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gt2whkzqmac.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2pevdljfk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gt2tfwwuiey.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2cxagpppi.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2zintihsh.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gt2spxgqzow.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2pvrnasad.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gt2liyoqzee.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gt2rdaahney.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2ngaksxbj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pismrtik.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gt2kalknlyo.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gt2eomxvmgh.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gt2xwnwmdog.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wepnwaxl.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2fzkaapmq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjwilkxo.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gt2iymjxohg.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gt2obtnldzw.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gt2smzhtpgc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2hmcateyz.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gt2ehmemuvq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2ftuhqusk.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gt2rwdapbsb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gt2kthevvks.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2wlexnutk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gt2dcmourwz.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gt2yihzalro.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gt2jampyzen.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2wbacgmlp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gt2jpqkutwq.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gt2ylvhqvxl.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gt2zzksvlmr.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bugmhjlr.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcldqqxi.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gt2drkyplqc.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hchtjden.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gt2neywrvxw.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gt2bqvirysd.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2sbjwjqof.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gt2cvgsdbyp.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gt2wrthnffc.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gt2xfkjqffu.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnvoodis.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gt2rneeqymn.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2omkqmpkm.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gt2rdfbwzzc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyrohisl.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gt2gaszmozi.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2qcclquhe.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gt2mylhhxyl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gt2knrefnqj.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gt2jmzokorr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gt2lmwozwcd.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2wpeyxjpb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2awzwsinw.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gt2xqujessy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2nmgnssne.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljeoygyr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gt2uiqgwhjd.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gt2agnzetfb.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2badsvoep.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gt2ktsdbwhr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2fxapgaoy.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iiqgvbfu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gt2iaptrxug.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gt2kzjnbrqv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2xalydfms.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxcvdgwm.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gt2tznrhxaf.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gt2dpghfohz.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gt2vwycgsxc.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpwoyeyk.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gt2iotyzlja.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gt2aoehfkdl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gt2olbufoco.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gt2wtbxqoog.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gt2imlnbrxd.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2wquhuoya.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gt2ikxqrxzi.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2pjnifqvs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gt2zjtqmoos.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gt2xruvqkhl.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gt2gnvcpyxc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gt2cpujablf.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gt2wndpemkg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnovpxyh.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gt2tzcqfnrw.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gt2urlhwehy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnxpmrs.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2kurwvfqz.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gt2epgmpyen.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbnteufs.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gt2wvacvfex.html


<!-- 参考信息 -->