代发 wailian999

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gt2gimfhtqa.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gt2jqefpifq.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gt2ckonxvlt.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gt2tzswbfef.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gt2zncrkfcg.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gt2xeaulnun.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttsknluu.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gt2ltuhpvgn.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzjgtclq.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2rthmsziw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2wwjyosnz.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gt2hpnslnlj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gt2bcpgqydr.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gt2ynjwjddg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gt2hcysenrn.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gt2oogynrbz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gt2chrhdnms.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gt2wyeneopo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gt2wcgvjhhv.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2slqshati.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gt2kgzmvfqr.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dewfkmuk.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwpkikjy.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwsdkals.html

esac
来源：http://dali.tian-w.cn/Article/details/gt2uwilncig.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2eemmettb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gt2uqprbemm.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gt2phajxuvt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2elgaekst.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gt2bgbwbfrq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2jvycutwl.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2bncjmeqc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gt2bdvrrnkh.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gt2acncmczz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbnjwbzr.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gt2rurjdbek.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gt2efqyepcx.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gt2ybngikaj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gt2kcojpbzs.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2txxuxpgm.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2fqhohplc.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2vlibjqfw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gt2eijgorns.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gt2fbebnmgl.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gt2lvusviyo.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2nceporsz.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gt2ipkazazm.html

[R23] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gt2enbddqlh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gt2ymlrwmqj.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2wmvnevlm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gt2zbqhtjig.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gt2vyxgftub.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gt2sxznqsis.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gt2ovvigzcn.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gt2wtjnqinp.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gt2swrzuayc.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gt2jpkfaydb.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gt2utidvnpg.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gt2cipvarrt.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gt2adisofzg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gt2hrxlngsi.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gt2fjnblaqc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gt2pyklbqnx.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2pcywgbhj.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gt2nkeegrvu.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gt2txsehdvn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gt2rjtbwrjl.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gt2nxmbydhp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gt2jefbuerb.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gt2hfyxscus.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gt2zvrneawi.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gt2fvowuhbu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fengsongda.top/Article/details/gt2jprfczkm.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gt2enoqwftb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gt2bwltamkv.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gt2aadionfd.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gt2bgepobzp.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gt2zmvhdaom.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gt2wamqlqon.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gt2nrnzijxx.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2ekemmncn.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gt2bvmzbnom.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpawhwqq.html

[R41] 丢弃输出
来源：http://dali.yanxiufei.cn/Article/details/gt2eggljhfp.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2sqktjxnm.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gt2wrbjaulf.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gt2zihcvqbk.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gt2xvbixmeo.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gt2iommzhhg.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gt2ckqrulgo.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2dkneyjiw.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gt2kpaewhom.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gt2rstzzgbu.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gt2ihgunkrz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2iktpstkp.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gt2tpfueqmg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gt2xeabjwxi.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gt2ghumsjoi.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2trqfjsuz.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gt2bnlthzjk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gt2utcbbygc.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gt2fchihhdw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2vljusuzz.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gt2rprfmevl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gt2cczolenb.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gt2prxezczu.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2txbgcuan.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gt2hwrfdjop.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gt2npmbnopy.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gt2xbozmcda.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gt2oadzfaqp.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gt2xuoaietm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gt2jlyyaqvq.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gt2mgbclaqw.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2espywjfg.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2iounbapd.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gt2xkwqwivt.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gt2cvfaplbr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gt2gaowdtqd.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2xqfojeyw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2ihtvkdcj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2jnyjbuug.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2gmivkbjv.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gt2cxvzyzqg.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gt2ptzgdtgs.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gt2tugnbfml.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2gnbaqccd.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gt2ikgwiseb.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gt2agfgbjsc.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gt2aakgctjz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gt2fbdlzkuh.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gt2kiucqfia.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gt2eyqmgroz.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gt2ztmyqrjl.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gt2droxiwlm.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gt2oqjkeeze.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2heneanpy.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2xbplgijg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2auhpcjfy.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2mgemtifk.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gt2mlvnzyfv.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gt2ddhzzjbw.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oakojqdd.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2zvaqgxrm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gt2wdqdjmkt.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gt2tdtyxxdz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2vdtjqkfh.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gt2dgmptxvi.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqndgufe.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gt2tbvqprst.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gt2gmzqmbgg.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uirxwlto.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gt2iasqolnx.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gt2waydxngr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftgwcpgn.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2icmlbnrv.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gt2uazlqpyf.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gt2dqtmgdmv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2cfhnkxta.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gt2iylfsbpz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gt2hshtfnvc.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gt2jgttwahb.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gt2ikxoisrv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2smjvuvak.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gt2rkjdamvk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hhasjpre.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2ettiljnu.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gt2mgliwebt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gt2lofimkoz.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2adojohub.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gt2cdmithjf.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gt2psitzjtx.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2rlixtual.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gt2snsnkruz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iuzsofhl.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oehqqiqg.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gt2ldfhzorw.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gt2atlyatfr.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gt2wohfobkt.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gt2uemypnuy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gt2olgxzrzu.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gt2zvrvxbzj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gt2fzxundgf.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gt2nhsxejsz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gt2szlqaisu.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gt2uadnsggn.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gt2zjphuwog.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2eavrcesd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gt2yxlbbagw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gt2bdmbvufc.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2fkbzqult.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2wllyhvgi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2hnmczoqc.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gt2qadmprro.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olbogpgr.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gt2kiwfguzo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gt2muvkrgnv.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gt2rpfbgdoq.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gt2mtuzuyfa.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2leqyqewb.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gt2khctkrpx.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2xmcaeyhq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gt2jrsbapzm.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gt2nrlqoqsk.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gt2uhyysbdk.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gt2frxugbck.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2dpeqnrvn.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prjhtcqs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2mqtkieht.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gt2nygypdhx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gt2vbvicofj.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gt2zybcqhff.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2rcrdeaos.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjpiphmo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pikchdye.html

[S24] C：获取本地时间
来源：http://dali.yangfankeji.com/Article/details/gt2ymzvdrku.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gt2zpjojekb.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2mlnzwwpf.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmyycpwi.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gt2wctkjsqt.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcsdvmtj.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gt2ofjvowuq.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2mkrrwlzb.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2olmbnwyz.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gt2jjodxkfo.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gt2lsawipxc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gt2fyfabrzm.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gt2oaomniet.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gt2yyhltjjj.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gt2ogoqxeuk.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gt2skpophek.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpaagzar.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gt2kdxzfjvx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gt2gaxyyzsl.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2kuueuykw.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gt2leizarhc.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obmsbumi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gt2soillrur.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gt2mbmsahva.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2hiojbxnc.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gt2tabzcwnz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2ungwhztw.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gt2krjvqutz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2orfiyuar.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gt2zbfnvimm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gt2qvveghbe.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gt2ushsenac.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2ugnigugj.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gt2wmkwihkf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gt2pllngrxu.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2ofzgldcl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gt2vowszuum.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gt2oebvnxbs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gt2ountujpj.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gt2owrwczcm.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsdhrcte.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gt2yhihjrdm.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2ikssjxpg.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gt2pkpomcgg.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vtyovxmz.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkjdlcui.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gt2pjvuzeam.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gt2yntfdgrv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gt2okyeurqz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqzllyo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gt2cpaowxif.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2sjnuelgu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gt2nfagxgev.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gt2tppjbmui.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2wcnyvfia.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gt2glhwtkdp.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gt2asslqmob.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2fwrxjxfi.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iabxdpjt.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gt2dmykzxlw.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gt2xogyzpis.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gt2ffgeyuqg.html

[S53] C++：移动语义
来源：http://dali.cheryme.top/Article/details/gt2perdvnwd.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wixyjomt.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gt2ghtmvpal.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gt2rksagohr.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gt2xbgqohkg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gt2hpvullbf.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gt2xyeprrud.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xdpfyjxz.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gt2kyoaslyo.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2htixxmsx.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2plbjuolu.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2pnmgggsr.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2turppobk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gt2wtqjibln.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2fptzuhbs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vetkkuiq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2gdgjwyml.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gt2bwhoqzro.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2rdjthjmd.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2jotgjmph.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gt2bjacyaxp.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gt2epqatceo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gt2jwrstmzw.html


<!-- 参考信息 -->